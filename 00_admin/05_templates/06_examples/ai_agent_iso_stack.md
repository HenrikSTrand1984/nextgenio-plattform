# 📦 Komplett løsning: ISO-dokumentstyring med AI-agent, Supabase og Netlify

**Plassering:** `/00_admin/05_templates/06_examples/ai_agent_iso_stack.md`

## 🧠 Oversikt
En fullstack ISO-løsning med:
- 📄 Dokumentasjon i Markdown og YAML
- 🤖 AI-agent i Python med OpenAI SDK
- 🛢 Supabase (PostgreSQL) for lagring og spørring av dokumenter
- 🌐 Netlify + React for frontend-visning og statuskontroll
- 🔁 YAML-register for struktur og metadata

---

## 📁 Strukturen
```plaintext
├── agents/
│   └── quality_manager_agent.py         # AI-agent med OpenAI + Supabase
├── db/
│   └── supabase_schema.sql              # SQL-skjema for dokumentlagring
├── frontend/
│   ├── pages/
│   │   └── iso-overview.jsx             # React-side for å vise dokumentstatus
│   └── data/
│       └── iso_documents.yaml           # Metadata om dokumenter
├── register/
│   ├── versionslogg.yaml
│   └── quality_manager_agent.yaml
├── docs/
│   ├── procedures/
│   │   └── kvalitetskontroll.md
│   └── checklists/
│       └── leveranse_sjekkliste.md
```

---

## 🔍 YAML: `register/quality_manager_agent.yaml`
```yaml
agent:
  navn: QualityManagerAgent
  rolle: Overvåker ISO 9001 dokumenter
  input:
    - supabase: iso_documents
    - register: versionslogg.yaml
  triggere:
    - dokument_mangler
    - status_ikke_aktiv
    - versjon_utdatert
  output:
    - varsling
    - forbedringsforslag
```

---

## 📦 Supabase schema: `db/supabase_schema.sql`
```sql
create table iso_documents (
  dokument_id text primary key,
  navn text,
  type text,
  iso_punkt text,
  versjon text,
  status text,
  sist_revidert date,
  eier text,
  filsti text
);
```

---

## 🧠 Agent: `agents/quality_manager_agent.py`
```python
import openai, requests, os

SUPABASE_URL = os.getenv("SUPABASE_URL")
SUPABASE_KEY = os.getenv("SUPABASE_KEY")
HEADERS = {"apikey": SUPABASE_KEY, "Authorization": f"Bearer {SUPABASE_KEY}"}

def hent_dokumenter():
    r = requests.get(f"{SUPABASE_URL}/rest/v1/iso_documents?select=*", headers=HEADERS)
    return r.json()

def evaluer_med_openai(dokumenter):
    openai.api_key = os.getenv("OPENAI_API_KEY")
    melding = f"Evaluer disse dokumentene for ISO 9001-samsvar: {dokumenter}"
    response = openai.ChatCompletion.create(
        model="gpt-4",
        messages=[{"role": "system", "content": "Du er ISO-kvalitetsleder."},
                  {"role": "user", "content": melding}]
    )
    return response["choices"][0]["message"]["content"]

if __name__ == "__main__":
    docs = hent_dokumenter()
    vurdering = evaluer_med_openai(docs)
    print(vurdering)
```

---

## 🌐 Frontend (React): `frontend/pages/iso-overview.jsx`
```jsx
import React, { useEffect, useState } from 'react';

export default function ISOOverview() {
  const [docs, setDocs] = useState([]);
  useEffect(() => {
    fetch("https://xyz.supabase.co/rest/v1/iso_documents", {
      headers: { "apikey": "SUPABASE_KEY" }
    })
      .then(r => r.json())
      .then(setDocs);
  }, []);

  return (
    <div className="p-4">
      <h1 className="text-xl font-bold">ISO 9001-dokumenter</h1>
      <ul>
        {docs.map(doc => (
          <li key={doc.dokument_id}>{doc.navn} – {doc.status} (v{doc.versjon})</li>
        ))}
      </ul>
    </div>
  );
}
```

---

## 📜 Versjonslogg: `register/versionslogg.yaml`
```yaml
- dokument_id: ISO-PR-001
  navn: Kvalitetskontroll prosedyre
  versjon: 1.1
  dato: 2025-07-22
  endret_av: Henrik Strand
  endring: Justert kontrollpunkt 3 og 4
```

---

## ✅ Neste steg
- Deploy frontend til Netlify med API-key som env-variabel
- Kjør agent via CRON eller GitHub Action
- Lag Slack/epost-varsling fra agent hvis avvik finnes
- Koble flere dokumenttyper: policy, arbeidsinstruks, skjema

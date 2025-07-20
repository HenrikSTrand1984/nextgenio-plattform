# 🤖 [AGENTNAVN] – README

**Dokument-ID:** NG-AGENT-README-XXXX  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** [ÅÅÅÅ-MM-DD]  
**Plassering (GitHub):** `/agents/[agentnavn]/README.md`  
**Plassering (Dropbox/SharePoint):** NextGenio-plattform-[avdeling]/[sti-til-agentdokumentasjon]  

---

## 🎯 Formål

Denne README-filen dokumenterer agentens rolle, ansvar, funksjoner og implementasjonsdetaljer i NextGenio-systemet. Den følger retningslinjer fra TOGAF, ISO 15288, ISO 9001 og interne policyer for agentarkitektur, sikkerhet og dokumentasjonskvalitet.

> Eksempel:  
> Agenten fungerer som **Kvalitetsleder**, med ansvar for policyer, prosesser og dokumentkontroll i henhold til ISO 9001 og NextGenios rammeverk.

---

## 🧩 Agentens rolle og funksjon

| Egenskap     | Verdi |
|--------------|-------|
| **Agentnavn** | [Navn, f.eks. Agent 1 – Kvalitetsleder] |
| **Primærrolle** | [F.eks. Policyansvar, Dokumentkontroll, ISO-overvåking] |
| **Kjerneansvar** | [Kort punktliste over ansvar] |
| **Systemtilgang** | [Supabase, OpenAI SDK, GitHub, osv.] |
| **Logger til** | [Supabase-DB, versjonslogg.yaml] |

---

## ⚙️ Funksjonalitet og komponenter

| Komponent | Beskrivelse | Type |
|----------|-------------|------|
| `create_assistant.py` | Oppretter agent med funksjonskall | Python |
| `functions.yaml` | Definerer funksjonsstruktur og input/output | YAML |
| `agent_config.json` | Konfigurasjonsdata (navn, API, metadata) | JSON |
| `logs/` | Mappe for agentens transaksjonslogger | Mappe |

---

## 🗺️ Arkitektur og integrasjoner

> Diagram (valgfritt): inkluder gjerne `.drawio` eller `.svg`-fil som visualiserer hvordan agenten inngår i systemet (C4- eller TOGAF-nivå 2/3).

| Integrasjon | Formål | Protokoll |
|-------------|--------|-----------|
| Supabase    | Logging, autentisering, RLS | PostgREST, JWT |
| OpenAI SDK  | Agentmotor | HTTPS / SDK |
| GitHub      | Versjonskontroll, policyhåndtering | REST API / Git |

---

## 🧪 Test og validering

- Teststatus: [F.eks. "Under utvikling", "Valideres med testdatasetter"]
- Testmiljø: [F.eks. Devcontainer, Hugging Face Space, Docker]

> Legg ved eventuelle `testlog.md`, `sample_input.json`, `mock_data.yaml`.

---

## 🔐 Sikkerhet og tilgang

| Område | Beskrivelse |
|--------|-------------|
| Autentisering | Supabase Auth eller API-nøkkel |
| Roller | [Eksempel: `agent_kvalitet`, `admin`, `readonly`] |
| Tilgangskontroll | RLS-policy definert i `supabase_sikkerhet.yaml` |
| Datainnsyn | Begrenset til tildelte roller |

---

## 📚 Relaterte dokumenter og mapper

- `/admin/governance/dokumentpolicy.md` – Agentens referansepolicy
- `/admin/roles/kvalitetsleder.md` – Rollen agenten representerer
- `/docs/architecture/agentstruktur.drawio` – Visuell arkitektur
- `/scripts/agents/` – Funksjonskode og API-integrasjon

---

## 📄 Dokumentkontroll

| Felt           | Innhold              |
|----------------|----------------------|
| Opprettet av   | [Navn]               |
| Revidert av    | [Navn]               |
| Godkjent av    | [Navn], [Navn]       |
| Sist oppdatert | [ÅÅÅÅ-MM-DD]         |
| Versjonslogg   | Se `versjonslogg.yaml` eller `policy_register.md` |


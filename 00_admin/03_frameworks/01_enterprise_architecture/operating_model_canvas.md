# ⚙️ Operating Model Canvas – Strategi til drift i NextGenio

**Dokument-ID:** NG-FRM-EA-OMC-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-21  
**Plassering:** `/00_admin/03_frameworks/01_enterprise_architecture/operating_model_canvas.md`  
**Eier:** Arkitekturansvarlig  

---

## 🎯 Formål

**Operating Model Canvas** (OMC) brukes i NextGenio som verktøy for å **designe og visualisere hvordan strategi omsettes til drift**. Det gir en strukturert måte å koble forretningsmål til organisering, prosesser og teknologi – og brukes aktivt ved planlegging av AI-agenter og datastruktur.

---

## 🧱 Modellens hovedkomponenter

| Komponent         | Hva det betyr                     | NextGenio-eksempel |
|------------------|------------------------------------|--------------------|
| **Customer Experience** | Hvordan brukere opplever tjenestene | Dashbord, AI-agent UI |
| **Processes**     | Kjerneprosesser som må utføres     | Avviksbehandling, dokumentflyt |
| **Organization**  | Struktur og roller                 | Agentarkitektur, RACI-roller |
| **Location**      | Hvor jobben gjøres                 | Skybasert (Supabase, GitHub), kontor for ledelse |
| **Information**   | Hvilken informasjon som trengs     | ISO-dokumenter, agentlogger, OKR |
| **Suppliers**     | Eksterne bidragsytere              | OpenAI, ClickUp, Netlify |
| **Management System** | Hvordan styres og følges opp | OKR, ISO, policyer, agentovervåking |

---

## 🧩 Bruksområder i NextGenio

- Planlegging av nye **moduler og agenter**
- Design av **MVP og roadmap**
- Struktur for **compliance-oppfølging**
- Bro mellom TOGAF-fase A (visjon) og B–D (arkitektur)

---

## 🖼️ Visualisering

Canvasen lages gjerne som et tabelloppsett med relasjoner mellom komponentene.

Plasseres i:
- `/docs/architecture/operating_model_canvas.drawio`
- Alternativt som YAML/Markdown i `canvas_model.yaml`

---

## 🔗 Relasjoner

| Brukes sammen med | Fil / Rammeverk |
|-------------------|------------------|
| Kapabilitetskart  | `business_capability_map.md` |
| Agentroller       | `agent_register.md` |
| DevOps strategi   | `supabase_forklaring.md` |
| TOGAF fase A      | `togaf_framework.md` |

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                  |
|------------------|-------------------------------------------|
| Opprettet av     | Henrik Strand                             |
| Revidert dato    | 2025-07-21                                |
| Versjon          | 1.0                                       |
| Status           | Aktiv                                     |
| GitHub-plassering| `/00_admin/03_frameworks/01_enterprise_architecture/` |

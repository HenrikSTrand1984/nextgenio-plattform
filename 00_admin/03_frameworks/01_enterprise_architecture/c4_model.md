# 🧩 C4 Model – Visualisering av systemarkitektur i NextGenio

**Dokument-ID:** NG-FRM-EA-C4-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-21  
**Plassering:** `/00_admin/03_frameworks/01_enterprise_architecture/c4_model.md`  
**Eier:** Arkitekturansvarlig  

---

## 🎯 Formål

C4-modellen gir et presist og standardisert rammeverk for **visuell systemarkitektur**. Den brukes i NextGenio for å beskrive og kommunisere strukturen i agentbaserte og modulære løsninger, i tråd med TOGAF og Supabase-integrasjoner.

---

## 🧱 De fire nivåene i C4

| Nivå       | Fokusområde                            | Beskrivelse |
|------------|-----------------------------------------|-------------|
| **1. Context**   | Helhetlig kontekst                   | Viser hvordan systemet samhandler med eksterne aktører og systemer |
| **2. Container** | Teknologiske containere og moduler   | Viser hvilke containere (eks: API, database, frontend) systemet består av |
| **3. Component** | Interne komponenter                  | Viser hvordan hver container er strukturert og hvilke funksjoner som inngår |
| **4. Code**      | Kode-nivå (valgfritt)                | Teknisk diagram på klasse-/filnivå – brukes ved behov for dyp dokumentasjon |

---

## 🖼️ Eksempelbruk i NextGenio

- Nivå 1: **NextGenio som system** med eksterne brukere, Supabase og OpenAI-integrasjon
- Nivå 2: **Gradio frontend**, **API-backend**, **Supabase DB**, **auth-container**
- Nivå 3: **Agentlogikk**, **logging-komponent**, **ISO-arkivmodul**, **OKR-modul**
- Nivå 4: Ved behov – typisk brukt i `scripts/agents/` og spesifikke helper-moduler

---

## 🔧 Verktøy som støtter C4

- [Structurizr](https://structurizr.com/)
- [PlantUML](https://plantuml.com/c4)
- [Draw.io](https://app.diagrams.net/)
- Markdown + Mermaid i GitHub (`c4.mmd`)

---

## 🧩 Integrasjon med andre rammeverk

C4 visualisering gir støtte og konkretisering til:

- **TOGAF**: Visualisering av fasestruktur og teknologiarkitektur (fase D)
- **ArchiMate**: Kan oversettes mellom notasjonene ved behov
- **ISO 27001 og 9001**: Dokumentasjon av sikkerhetslag og kvalitetssikrede moduler

---

## 📎 Relaterte filer

- `/docs/architecture/c4_system.mmd`
- `togaf_framework.md`
- `supabase_forklaring.md`
- `gradio_architecture.md`

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                  |
|------------------|-------------------------------------------|
| Opprettet av     | Henrik Strand                             |
| Revidert dato    | 2025-07-21                                |
| Versjon          | 1.0                                       |
| Status           | Aktiv                                     |
| GitHub-plassering| `/00_admin/03_frameworks/01_enterprise_architecture/` |

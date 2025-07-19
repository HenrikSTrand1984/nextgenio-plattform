# 📘 Policy: Dokumentstruktur i NextGenio-plattformen

**Dokument-ID:** NG-GOV-POLICY-STRUKTUR-0001  
**Versjon:** 1.1  
**Status:** Aktiv  
**Dato:** 2025-07-19  
**Dokumenteier:** Henrik Strand – Kvalitetsleder, NextGenio  
**Plassering GitHub:** `/admin/governance/dokumentstruktur_policy.md`  
**Plassering Dropbox/SharePoint:** `/NextGenio-plattform-09-Documetations-01-Documentstructure/dokumentstruktur_policy.md`  

---

## 🎯 Formål

Denne policyen definerer **standardisert dokument- og mappestruktur** for alle repositorier og områder i NextGenio-plattformen. Målet er å sikre:

- Etterprøvbarhet og kvalitet i dokumentasjon
- Sammenheng mellom GitHub, Dropbox og SharePoint
- Sporbarhet iht. ISO 15489, 30301 og 27001
- Klar versjonskontroll og eierskap

---

## 📁 Strukturprinsipper

| Prinsipp                      | Beskrivelse |
|------------------------------|-------------|
| 📦 **Modulær struktur**       | Alle mapper har tydelig funksjon og begrenset omfang |
| 🧠 **README.md obligatorisk** | Forklarer struktur, eierskap og formål |
| 🆔 **Metadata på dokumenter** | Dokument-ID, versjon, status, eier, dato |
| 🧾 **Versjonslogg**           | Endringer logges i `versjonslogg.yaml` |
| 🔁 **Dobbel lagring**         | Alt lagres i GitHub + Dropbox/SharePoint |
| 🧱 **Standard maler**         | Bruk av `readme_mappe_template.md` og tilhørende maler |

---

## 📚 Formatkrav og filtyper

Se full oversikt i vedlegg: `definisjoner_inkl_vedlegg.md`.

Eksempler:
- `.py`, `.js`, `.yaml`, `.md`, `.pdf`, `.mmd`, `.drawio`, `.schema`, `.json`
- `.env.example`, `Dockerfile`, `docker-compose.yml`

Se også: `formatkrav_dokumentasjon_vs_kode.md` for detaljert tabell.

---

## 📂 Mappetyper og konvensjoner

| Mappe           | Innhold og hensikt | Mal |
|------------------|--------------------|------|
| `admin/`         | Governance, policy, standarder | `readme_mappe_template.md` |
| `docs/`          | Arkitektur, diagrammer og dokumentasjon | `readme_mappe_template.md` |
| `guides/`        | Brukerveiledninger og forklaringer | `readme_mappe_template.md` |
| `scripts/`       | Agentkode, API, test, utils | `readme_mappe_template.md` |
| `agents/`        | Hver AI-agent med egen struktur | `readme_agent_template.md` |
| `output/`        | Eksporterte rapporter og filer | Enkel README |
| `integrations/`  | Systemoversikt og eksterne koblinger | `readme_mappe_template.md` |
| `devcontainer/`  | Miljøoppsett og kodeutvikling | `readme_mappe_template.md` |

---

## 🧱 Krav per mappe

- **README.md**: Forklarer innhold og eier
- **Eier**: Definert person (CPO Henrik Strand til standard)
- **Filstruktur**: Små bokstaver, engelsk navn, ingen mellomrom
- **Versjonslogg**: Bruk `versjonslogg.yaml` ved endringer
- **Referanser**: Lenker til policyer og maler

---

## 🛡️ Forvaltningspraksis

- Strukturendringer skal godkjennes av **Kvalitetsleder**
- Nye mapper skal vurderes ift. eksisterende standarder
- All dokumentasjon skal følge **ISO 15489, 30301 og 27001**
- Dokument-ID-er skal følge `NG-GOV-*`-konvensjon

---

## 📚 Relaterte dokumenter

- `/admin/governance/readme_policy.md`
- `/admin/governance/dokumentpolicy.md`
- `/admin/governance/versjonslogg.yaml`
- `/admin/standarder/lagringsstandarder.md`
- `/admin/templates/readme_mappe_template.md`
- `definisjoner_inkl_vedlegg.md`
- `formatkrav_dokumentasjon_vs_kode.md`

---

## 📄 Dokumentkontroll

| Felt              | Innhold |
|-------------------|---------|
| **Dokument-ID**   | NG-GOV-POLICY-STRUKTUR-0001 |
| **Versjon**       | 1.1 |
| **Status**        | Aktiv |
| **Opprettet**     | 2025-07-19 |
| **Sist revidert** | 2025-07-19 |
| **Godkjent dato** | 2025-07-19 |
| **Dokumenteier**  | Henrik Strand – Kvalitetsleder, NextGenio |
| **Godkjent av**   | Henrik Strand & AI Assistant |
| **Logg**          | Registrert i `versjonslogg.yaml` og Supabase-autentisert |

---

## 🌐 Plassering

| Miljø        | Sti |
|--------------|-----|
| **GitHub**   | `/admin/governance/dokumentstruktur_policy.md` |
| **Dropbox**  | `/NextGenio-plattform-09-Documetations-01-Documentstructure/dokumentstruktur_policy.md` |

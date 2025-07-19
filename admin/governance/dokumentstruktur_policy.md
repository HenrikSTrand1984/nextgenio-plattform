# 📘 Policy: Dokumentstruktur og mappestandard i NextGenio

**Dokument-ID:** NG-GOV-POLICY-STRUKTUR-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-19  
**Dokumenteier:** Henrik Strand – Kvalitetsleder, NextGenio  
**Plassering GitHub:** `/admin/governance/dokumentstruktur_policy.md`  
**Plassering Dropbox/SharePoint:** `/NextGenio-plattform-09-Documetations-01-Documentstructure/dokumentstruktur_policy.md`  

---

## 🎯 Formål

Definere **standardisert mappestruktur og dokumentplassering** for alle prosjekter, repositorier og områder i NextGenio. Dette skal sikre **etterprøvbarhet, gjenfinning, kontroll og kontinuitet** i hele organisasjonens informasjonsforvaltning – i tråd med ISO 15489, ISO 30301 og ISO 27001.

---

## 📁 Strukturprinsipper

| Prinsipp | Beskrivelse |
|---------|-------------|
| **Modulær struktur** | Hver mappe skal ha klart avgrenset formål og funksjon |
| **Dokument-ID og metadata** | Alle styrende dokumenter skal ha ID, versjon, eier, dato og status |
| **Eierskap og RACI** | Alle mapper og dokumenter skal ha definert eier |
| **To lagringssteder** | Alt lagres både i GitHub og Dropbox/SharePoint |
| **README.md i hver mappe** | Forklarer innhold, formål, eier og struktur |

---

## 🗂️ Mappetyper og konvensjon

| Mappenavn | Formål og innhold | README-mal |
|-----------|-------------------|------------|
| `admin/` | Governance, policy, standarder og interne styringsfiler | `readme_mappe_template.md` |
| `docs/` | Arkitektur, diagrammer, dokumentasjon og forklaringer | `readme_mappe_template.md` |
| `scripts/` | Kode og logikk for agenter, API-er, test og databehandling | `readme_mappe_template.md` |
| `guides/` | Brukerveiledninger og forklaringer (eks: Supabase, Jenkins) | `readme_mappe_template.md` |
| `agents/` | Hver AI-agent med egen struktur og README | `readme_agent_template.md` |
| `output/` | Eksporterte rapporter, diagrammer, word-filer etc. | Enkel README |
| `integrations/` | Oversikt over integrasjoner (ikke kode) | `readme_mappe_template.md` |

---

## 🧱 Strukturkrav i mapper

Alle hovedmapper skal inneholde:

- `README.md`
- Klar rollefordeling (eier og ansvar)
- Submapper med klart navngivingsmønster (små bokstaver, engelsk)
- Bruk av `versjonslogg.yaml` for kritiske dokumenter
- Koblede referanser til relevante policyer og metoder

---

## 🛡️ Forvaltningspraksis

- Strukturendringer skal godkjennes av Kvalitetsleder
- Nye mapper skal alltid vurderes i lys av eksisterende struktur
- ISO 30301 benyttes som styrende rammeverk for informasjonsstyring
- Dropbox-/SharePoint-struktur skal speile GitHub-struktur, med justert mappenavn der nødvendig

---

## 📚 Relaterte dokumenter

- `/admin/governance/readme_policy.md`  
- `/admin/governance/dokumentpolicy.md`  
- `/admin/standarder/lagringsstandarder.md`  
- `/admin/governance/versjonslogg.yaml`  
- `/admin/templates/readme_mappe_template.md`  
- ISO 15489, ISO 30301, ISO 27001

---

## 📄 Dokumentkontroll

| Felt | Innhold |
|------|---------|
| **Dokument-ID** | NG-GOV-POLICY-STRUKTUR-0001 |
| **Versjon** | 1.0 |
| **Status** | Aktiv |
| **Opprettet** | 2025-07-19 |
| **Sist revidert** | 2025-07-19 |
| **Godkjent dato** | 2025-07-19 |
| **Dokumenteier** | Henrik Strand – Kvalitetsleder, NextGenio |
| **Godkjent av** | Henrik Strand & AI Assistant |
| **Logg** | Registrert i `versjonslogg.yaml` og Supabase-autentisert |

---

## 📂 Plassering

| Miljø | Sti |
|-------|-----|
| **GitHub** | `/admin/governance/dokumentstruktur_policy.md` |
| **Dropbox / SharePoint / OneDrive** | `/NextGenio-plattform-09-Documetations-01-Documentstructure/dokumentstruktur_policy.md` |

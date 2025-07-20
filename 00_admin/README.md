# 🧭 Administrasjonsområde – `00_admin/`

**Dokument-ID:** NG-ROOT-README-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-20  
**Plassering:** `/00_admin/README.md`  
**Dropbox / SharePoint:** `NextGenio-plattform/00_Admin/`  
**Eier:** Henrik Strand – Kvalitetsleder

---

## 🎯 Formål

Denne mappen representerer det administrative kjernelaget i NextGenio-plattformen. Her dokumenteres styrende retningslinjer, roller, strukturer, ISO-rammeverk og metoder som legger grunnlaget for intern forvaltning, kvalitet, compliance og agentintegrasjon.

Innholdet er strukturert i tråd med ISO 9001, 15489, 27001 og 30301.

---

## 📂 Mappestruktur og innhold

```plaintext
00_admin/
│
├── README.md                             ← Overordnet intro til admin-domenet
│
├── 01_governance/                        ← Styring, ansvar, roller og policyer
│   ├── README.md
│   ├── governance_frameworks_summary.md         ← ISO 37000, COSO, OECD osv.
│   ├── policy_register.md                       ← Oversikt over styrende policyer
│   ├── dokumentpolicy.md                        ← Policy for dokumentforvaltning
│   ├── godkjenning_policy.md                    ← Regler for dokumentgodkjenning og eierskap
│   └── 02_rollebeskrivelser/                    ← Definerte roller brukt i governance og RACI
│       ├── README.md
│       ├── kvalitetsleder.md
│       ├── systemansvarlig.md
│       ├── complianceansvarlig.md
│       └── ...
│
├── 02_iso/                               ← ISO-standarder implementert i NextGenio
│   ├── README.md
│   ├── iso_9001_summary.md                      ← Kvalitetsledelse
│   ├── iso_27001_summary.md                     ← Informasjonssikkerhet
│   ├── iso_15489_summary.md                     ← Dokumentforvaltning
│   ├── iso_register.md                          ← Oversikt og status for ISO-bruk
│   └── ...
│
├── 03_frameworks/                        ← Rammeverk som TOGAF, OKR, C4, RACI, PDCA
│   ├── README.md
│   ├── togaf_summary.md                        ← Arkitektur og styring
│   ├── c4_model_summary.md                     ← Systemvisualisering
│   ├── okr_framework.md                        ← Målstyring
│   ├── raci_framework.md                       ← Rolle- og ansvarsmatriser
│   └── ...
│
├── 04_methods/                           ← Praktiske og analytiske metoder
│   ├── README.md
│   ├── 5whys.md                                ← Rotårsaksanalyse
│   ├── swot_analysis.md                        ← Strategisk vurdering
│   ├── lean_startup.md                         ← Innovasjonsmetodikk
│   └── ...
```

---

## 📘 Prinsipper

- 📎 All dokumentasjon er versjonsstyrt og strukturert
- 📄 Policyer og prosedyrer følger ISO-krav og er koblet til roller og ansvar
- 🤖 Filer er agenttilgjengelige der relevant (basert på YAML-registrering og policy)
- 📚 Mappen bygger på dokumentpolicy og godkjenningspolicy

---

## 🔗 Relaterte toppnivåmapper

- `docs/` – For operativ dokumentasjon, guider og referanser
- `devops/` – For teknisk drift, infrastruktur og CI/CD
- `integrations/` – For systemintegrasjoner og API-koblinger

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                       |
|------------------|-----------------------------------------------|
| Opprettet av     | Henrik Strand                                 |
| Godkjent av      | Henrik Strand, [navn 2]                       |
| Revidert dato    | 2025-07-20                                    |
| Versjonslogg     | Registrert i `versionslogg.yaml`              |


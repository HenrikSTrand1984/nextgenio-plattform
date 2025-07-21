
# 📘 Administrativ Struktur – NextGenio Plattform

**Dokument-ID:** NG-ADM-README-0001  
**Versjon:** 1.2  
**Status:** Aktiv  
**Dato:** 2025-07-20  
**Plassering GitHub:** `/00_admin/README.md`  
**Dropbox / SharePoint:** `NextGenio-plattform/00-Admin/`  
**Eier:** Henrik Strand / Kvalitetsleder  

---

## 🎯 Formål

Denne administrative katalogen utgjør det styrende fundamentet for NextGenio-plattformen. Her defineres rammeverk, metoder, roller, ISO-standarder og styrende policyer som gjelder for hele organisasjonen og agentarkitekturen.

---

## 📂 Mappestruktur

```plaintext
00_admin/
├── README.md                          ← Overordnet intro til admin-domenet
│
├── 01_governance/                     ← Styring, ansvar, roller og policyer
│   ├── README.md
│   ├── 01_frameworks/
│   │   └── README.md
│   ├── 02_policies/
│   │   ├── README.md
│   │   ├── dokumentpolicy.md
│   │   ├── godkjenning_policy.md
│   ├── 03_policy_register/
│   │   ├── README.md
│   │   └── policy_register.md
│   └── 04_role_descriptions/
│       ├── README.md
│       ├── kvalitetsleder.md
│       ├── systemansvarlig.md
│       ├── complianceansvarlig.md
│
├── 02_iso/                            ← ISO-standarder implementert i NextGenio
│   ├── README.md
│   ├── iso_folder_structure.md
│   ├── 01_iso_9001_quality/
│   │   └── README.md
│   ├── 02_iso_27001_security/
│   │   └── README.md
│   ├── 03_iso_15489_records/
│   │   └── README.md
│   ├── 04_iso_30301_governance/
│   │   └── README.md
│   ├── 05_iso_19475_digitaldocs/
│   │   └── README.md
│   └── 06_iso_register/
│       ├── README.md
│       └── iso_register.md
│
├── 03_frameworks/                     ← Rammeverk brukt i arkitektur, styring og utvikling
│   ├── README.md
│   ├── 01_enterprise_architecture/
│   │   └── README.md
│   ├── 02_roles_and_governance/
│   │   └── README.md
│   ├── 03_objectives_and_metrics/
│   │   └── README.md
│   ├── 04_quality_and_process/
│   │   └── README.md
│   └── 05_templates/
│       └── README.md
│
├── 04_methods/                        ← Praktiske og analytiske metoder
│   ├── README.md
│   ├── 01_problem_solving/
│   │   └── README.md
│   ├── 02_strategic_analysis/
│   │   └── README.md
│   ├── 03_process_improvement/
│   │   └── README.md
│   ├── 04_decision_support/
│   │   └── README.md
│   └── 05_templates/
│       └── README.md
│
└── 05_templates/                      ← Samlet malstruktur for rammeverk, metoder, ISO og YAML
    ├── README.md
    ├── 01_frameworks/
    │   └── README.md
    ├── 02_methods/
    │   └── README.md
    ├── 03_iso/
    │   └── README.md
    ├── 04_policies/
    │   └── README.md
    ├── 05_yaml/
    │   └── README.md
    ├── 06_examples/
    │   └── README.md
    └── 07_legacy/
        └── README.md
```

---

## 📎 Standarder og policyer som gjelder for denne mappen

| Standard | Formål |
|----------|--------|
| ISO 9001 | Kvalitetsledelse og dokumentert informasjon |
| ISO 30301 | Ledelsessystem for dokumentasjonsstyring |
| ISO 15489 | Records management – kontroll, sporbarhet |
| ISO 27001 | Informasjonssikkerhet – tilganger og revisjon |
| ISO 19475 | Digital dokumentlagring og uthenting |

---

## 🧠 Tips

- Alle `README.md`-filer følger standardmal og versjonskontrolleres  
- Dokument-ID tildeles ved opprettelse og legges inn i YAML-header  
- Maler finnes i `05_templates/` og skal brukes ved oppretting av nye rammeverk/metoder

---

## 📄 Dokumentkontroll

| Felt             | Innhold                            |
|------------------|-------------------------------------|
| Opprettet av     | Henrik Strand                       |
| Revidert dato    | 2025-07-20                          |
| Versjon          | 1.2                                 |
| Status           | Aktiv                               |
| GitHub-plassering| `/00_admin/README.md`               |
| Dropbox-plassering | `NextGenio-plattform/00-Admin/`  |

# 📘 Administrativ Struktur – NextGenio Plattform

**Dokument-ID:** NG-ADM-README-0001  
**Versjon:** 1.3  
**Status:** Aktiv  
**Dato:** 2025-07-21  
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
├── 00_register/                       ← Oversiktsregistre (policy, agenter, dokumentklasser)
│   ├── 01_policy_registers/
│   ├── 02_frameworks_registers/
│   ├── 03_methods_registers/
│   ├── 04_template_registers/
│   ├── 05_agent_registers/
│   └── 06_document_classes/
│
├── 01_governance/                     ← Styring, ansvar, roller og policyer
│   ├── 01_frameworks/
│   ├── 02_policies/
│   │   ├── dokumentpolicy.md
│   │   ├── godkjenning_policy.md
│   ├── 03_policy_register/
│   │   └── policy_register.md
│   └── 04_role_descriptions/
│       ├── kvalitetsleder.md
│       ├── systemansvarlig.md
│       ├── complianceansvarlig.md
│
├── 02_iso/                            ← ISO-standarder implementert i NextGenio
│   ├── 01_summaries/
│   ├── 02_structure_control/
│   ├── 03_implementation_logs/
│   ├── 04_templates/
│   └── 05_metadata/
│
├── 03_frameworks/                     ← Rammeverk brukt i arkitektur, styring og utvikling
│   ├── 01_enterprise_architecture/
│   ├── 02_roles_and_governance/
│   ├── 03_objectives_and_metrics/
│   ├── 04_quality_and_process/
│   └── 05_templates/
│
├── 04_methods/                        ← Praktiske og analytiske metoder
│   ├── 01_problem_solving/
│   ├── 02_strategic_analysis/
│   ├── 03_process_improvement/
│   ├── 04_decision_support/
│   └── 05_templates/
│
├── 05_templates/                      ← Samlet malstruktur for rammeverk, metoder, ISO og YAML
│   ├── 00_registers/
│   ├── 01_frameworks/
│   ├── 02_methods/
│   ├── 03_iso/
│   ├── 04_policies/
│   ├── 05_yaml/
│   ├── 06_examples/
│   ├── 07_agents/
│   ├── 08_checklists/
│   ├── 09_documents/
│   ├── 10_architecture/
│   ├── 11_legacy/
│   └── 12_data_models/
│
└── 06_business/                       ← Forretningsutvikling og strategiske dokumenter
    ├── 01_business_plans/
    ├── 02_investor_materials/
    ├── 03_market_analysis/
    ├── 04_business_models/
    ├── 05_jurisdiction_strategy/
    └── 06_customer_segments/
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
- Dokument-ID tildeles ved opprettelse og legges inn i YAML-header eller tabell  
- Maler finnes i `05_templates/` og skal brukes ved oppretting av nye rammeverk/metoder  
- Registere for alle hovedtyper ligger i `00_register/`

---

## 📄 Dokumentkontroll

| Felt             | Innhold                            |
|------------------|-------------------------------------|
| Opprettet av     | Henrik Strand                       |
| Revidert dato    | 2025-07-21                          |
| Versjon          | 1.3                                 |
| Status           | Aktiv                               |
| GitHub-plassering| `/00_admin/README.md`               |
| Dropbox-plassering | `NextGenio-plattform/00-Admin/`  |

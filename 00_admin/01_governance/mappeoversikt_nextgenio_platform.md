# 📂 Mappeoversikt – NextGenio-plattform

| Felt             | Innhold                                                   |
|------------------|------------------------------------------------------------|
| **Dokument-ID**  | NG-GOV-STRUCT-0001                                         |
| **Versjon**      | 1.0                                                        |
| **Status**       | Aktiv                                                      |
| **Dato**         | 2025-07-20                                                 |
| **Plassering**   | `/00_admin/01_governance/mappeoversikt_nextgenio_platform.md` |
| **Eier**         | Henrik Strand / Kvalitetsleder                             |

---

## 🎯 Formål

Dette dokumentet gir en samlet oversikt over mappestrukturen i hovedrepoet `nextgenio-platform/`, med forklaring av hver mappe og hvilken strukturpolicy den følger.  
Strukturen kombinerer nummererte og ikke-nummererte undermapper etter prinsippet om hybrid nummerering (se `mappepolicy.md`).

---

## 📦 Mappestruktur (med hybrid nummerering)

```plaintext
nextgenio-platform/
├── 00_admin/
│   ├── 01_governance/
│   ├── 02_iso/
│   ├── 03_frameworks/
│   ├── 04_methods/
│   └── 05_templates/
│
├── 01_devops/
│   ├── ci_cd/
│   ├── environments/
│   ├── testing/
│   ├── agent_ops/
│   ├── git/
│   └── templates/
│
├── 02_docs/
│   ├── 01_api/
│   ├── 02_architecture/
│   ├── 03_data_models/
│   ├── 04_sequence_diagrams/
│   └── 05_user_guides/
│
├── 03_integrations/
│   ├── supabase/
│   ├── openai/
│   ├── dropbox/
│   ├── github/
│   └── slack/
│
├── 04_quality_system/
│   ├── 01_procedures/
│   ├── 02_audits/
│   ├── 03_nonconformities/
│   └── 04_improvement/
│
├── 05_output/
│   ├── reports/
│   ├── exports/
│   └── logs/
│
├── 06_knowledgebase/
│   ├── 01_methods/
│   ├── 02_frameworks/
│   ├── 03_iso_standards/
│   └── 04_ai_models/
│
├── 07_agents/
│   ├── 01_kvalitetsleder/
│   ├── 02_research_assistant/
│   └── 03_project_manager/
│
├── 08_architecture/
│   ├── 01_togaf/
│   ├── 02_c4/
│   └── 03_system_diagrams/
│
├── 09_templates/
│   ├── markdown/
│   ├── yaml/
│   ├── docx/
│   ├── json/
│   └── policy/
│
└── 10_experiments/
    ├── llm_training/
    ├── prototypes/
    └── sandbox/

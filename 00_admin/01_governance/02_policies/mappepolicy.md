# 🗂️ Policy for mappearkitektur og mappestruktur i NextGenio

| Felt             | Innhold                                                  |
|------------------|-----------------------------------------------------------|
| **Dokument-ID**  | NG-GOV-POL-0005                                           |
| **Versjon**      | 1.0                                                       |
| **Status**       | Aktiv                                                     |
| **Dato**         | 2025-07-20                                                |
| **Eier**         | Henrik Strand / Kvalitetsleder                            |
| **Plassering**   | `/00_admin/01_governance/02_policies/mappepolicy.md`     |

---

## 🎯 Formål

Formålet med denne policyen er å etablere en enhetlig, etterprøvbar og ISO-samsvarende struktur for alle mapper og filer i NextGenio-prosjektet. Dette skal sikre oversikt, ansvarlighet, agenttilgang, standardisering og effektiv samhandling mellom dokumentasjon, kode og organisasjonsstyring.

---

## 🧱 Grunnprinsipper

Denne policyen bygger på følgende standarder og prinsipper:

- **ISO 9001** – Kvalitetsstyring og dokumentert informasjon
- **ISO 30301 / 15489** – Dokumentarkitektur og arkivstruktur
- **TOGAF og C4-modellen** – Arkitekturdokumentasjon og visualisering
- **Best practices fra GitHub** – Lesbar, skalerbar mappestruktur

---

## 📐 Retningslinjer for mappestruktur

### 1. 📁 Nummererte rotmapper
Alle hovedmapper i repoet skal ha **toppreffiks (00–99)** etter funksjon:

| Mappe           | Formål                                        |
|-----------------|-----------------------------------------------|
| `00_admin/`      | Styrende dokumentasjon og strukturkontroll    |
| `01_devops/`     | Drift, CI/CD, systemadministrasjon            |
| `02_docs/`       | Systemdokumentasjon og arkitektur             |
| `03_integrations/`| Tredjeparts- og systemintegrasjoner          |
| `04_quality_system/` | ISO 9001 implementering og prosessstyring |
| `05_output/`     | Genererte dokumenter og eksportfiler          |
| `06_knowledgebase/` | Kunnskapsbase, metoder, standarder         |
| `07_agents/`     | Dokumentasjon av AI-agenter og funksjoner     |
| `08_architecture/` | TOGAF og C4-baserte systembeskrivelser      |
| `09_templates/`  | Standardmaler (Markdown, YAML, docx)          |
| `10_experiments/`| Forsknings- og prototypearbeid                |

> Nye mapper skal følge samme nummereringslogikk for konsistens og sortering.
...

## 🔢 Retningslinjer for nummerering av undermapper

For å balansere struktur og fleksibilitet benyttes en hybrid tilnærming til nummerering:

| Bruk              | Prinsipp                                                                 |
|-------------------|--------------------------------------------------------------------------|
| ✅ Nummerering     | Brukes i mapper der struktur, rekkefølge eller ISO-kontroll er viktig (f.eks. `00_admin/`, `02_docs/`, `04_quality_system/`) |
| ❌ Ikke nummerering | Brukes i mapper med dynamisk eller teknisk karakter (f.eks. `01_devops/`, `03_integrations/`, `05_output/`) |

Alle nummererte mapper skal ha prefiks `01_`, `02_` osv. for å sikre sortering og etterprøvbarhet.

Ved tvil skal kvalitetsleder konsulteres.

## 🧭 Bestemmelser
...

---

### 2. 📄 README.md i hver mappe

Hver mappe (inkl. undermapper) skal ha en `README.md`-fil som inneholder:

- 📌 Dokument-ID, versjon, dato, eier, plassering
- 📄 Dokumentkontroll (opprettet, revidert, godkjent av)
- 🎯 Formål og innhold
- 📎 Kobling til relevante standarder, rammeverk og roller

---

### 3. 🔐 Mappetilgang og agentstøtte

- Mappestrukturen er designet for å støtte **rolle- og agentstyrt tilgang**.
- Hver mappe skal kunne **tilordnes ansvar (RACI)** og være koblet til én eller flere agenter.
- Tilgangsstyring skal implementeres teknisk via GitHub-rettigheter, Supabase RLS eller lignende.

---

## 🧭 Bestemmelser

| Område                       | Retningslinje |
|-----------------------------|---------------|
| **Fil- og mappenavn**       | Bruk kun **engelsk**, små bokstaver og `snake_case` hvis nødvendig |
| **Plassering av filer**     | All funksjonell og styrende dokumentasjon skal ligge i dedikerte mapper – ingen løse filer i repo-roten |
| **Endringer i struktur**    | Skal dokumenteres i `mappeoversikt_nextgenio_platform.md` og versjoneres via `versjonslogg.yaml` |
| **Unntak**                  | Kun tillatt etter godkjenning av kvalitetsansvarlig og revisjon av dokumentpolicy |
| **Metadata-krav**           | Alle `README.md`-filer skal inneholde YAML-header eller metatabell med identifikasjon |

---

## 📎 Tilhørende dokumenter

- `dokumentpolicy.md`  
- `godkjenning_policy.md`  
- `versjonslogg.yaml`  
- `mappeoversikt_nextgenio_platform.md`

---

## 📄 Dokumentkontroll

| Felt            | Innhold                    |
|-----------------|----------------------------|
| Opprettet av    | Henrik Strand              |
| Revidert dato   | 2025-07-20                 |
| Godkjent av     | [Fyll inn godkjenner]      |
| Status          | Aktiv                      |
| Versjon         | 1.0                        |
| Gjelder fra     | 2025-07-21                 |


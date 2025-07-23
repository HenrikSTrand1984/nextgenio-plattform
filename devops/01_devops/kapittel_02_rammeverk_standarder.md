# 📘 Kapittel 2: Rammeverk og standarder

**Dokument-ID:** NTG-DB-ARCH-PLATFORM-0002  
**Versjon:** 2.0  
**Status:** Ferdigstilt  
**Dato:** 2025-07-23  
**Plassering:** `/01_devops/03_supabase/kapittel_02_rammeverk_standarder.md`  
**Eier:** Henrik Strand / Norsain Technology Group  

---

## 🎯 Formål

Dette kapittelet dokumenterer hvilke standarder, rammeverk og prinsipper som ligger til grunn for hele Norsains dataplattformarkitektur. Det sikrer sporbarhet og etterlevelse gjennom strukturerte referanser.

---

## 📘 Sentral ISO- og regulatorisk forankring

| Standard / Regelverk     | Bruksområde                                             |
|---------------------------|----------------------------------------------------------|
| ISO 9001:2015             | Kvalitetsstyring og dokumenthåndtering                 |
| ISO/IEC 27001             | Informasjonssikkerhet og tilgangskontroll              |
| ISO/IEC 42001             | Styring av AI-systemer og forklarbarhet                |
| ISO 15489                | Dokumentasjonsstyring og arkiv                         |
| ISO/IEC 23894             | Risikostyring av AI og DLT                             |
| EU AI Act                | Kategorisering og risikohåndtering av AI-bruk           |
| ISO/IEC 27563 (kommende) | Etikk og bias-vurdering for AI-agentbeslutninger       |

---

## 🧱 Tekniske og metodiske rammeverk

| Rammeverk / Malverk           | Bruksområde                                        |
|-------------------------------|----------------------------------------------------|
| TOGAF                         | Enterprise Architecture                          |
| C4-modellen                   | Systemarkitektur og komponentvisualisering       |
| RACI-matrise                  | Rolle- og ansvarsklarhet                         |
| API-first prinsipp            | Modulær dataintegrasjon og migrerbarhet          |
| Zero-trust tilgangsprinsipp   | Supabase + GitHub policy                         |
| Design Science Research (DSR) | Forskningsbasert metodikk for agentstruktur      |
| ISO 56002 + ISO 56005         | Innovasjonsledelse og IP-dokumentasjon           |

---

## 📂 Metadata og koblingspunkter

| Register / Struktur             | Fil / Tabell                                 |
|----------------------------------|----------------------------------------------|
| Dokumentregister (QMS)          | `documents` tabell i Supabase                |
| Agentroller og ID-er            | `agent_register.yaml`                        |
| Standardreferanser               | `iso_compliance_matrix.md`                   |
| Prosessmappe og malarkiv        | `/02_iso/06_templates_and_models/`           |
| Patentsammenheng                | `platform_abstraction_layer.md`, kap. 17     |

---

## 📎 Neste steg

Kapittel 3 introduserer den tekniske arkitekturoversikten.

---
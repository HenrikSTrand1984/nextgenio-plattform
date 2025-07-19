# 📘 Dokumentstruktur og ID-konvensjon – NextGenio

| Felt              | Innhold                                                |
|-------------------|--------------------------------------------------------|
| **Dokument-ID**   | NG-DOK-STR-0001                                        |
| **Versjon**       | 1.1                                                    |
| **Status**        | Aktiv                                                  |
| **Dato**          | 2025-07-16                                             |
| **Eier**          | Henrik Strand / Kvalitetsansvarlig                     |
| **Plassering GitHub** | `/admin/dokumentstruktur/README.md`              |

---

## 🎯 Formål

Denne mappen definerer prinsipper og retningslinjer for hvordan dokumenter i NextGenio struktureres, navngis, identifiseres, versjonshåndteres og kobles til metadata.  
Den fungerer som styrende rammeverk for dokumentorganisering og informasjonsforvaltning.

---

## 🧭 Hensikt

- 📄 Sikre enhetlig praksis for dokument-ID og navnekonvensjon  
- 📁 Etablere strukturert og sporbar lagring på tvers av GitHub, Dropbox og Supabase  
- 🔍 Skape grunnlag for revisjon, automatisert validering og agentbasert dokumentforståelse  
- 📘 Oppfylle krav i ISO 15489, 30301, 27001 og 9001  

---

## 📦 Innhold i denne mappen

| Fil/Mappe                          | Innholdstype og funksjon |
|-----------------------------------|---------------------------|
| `README.md`                       | Dette dokumentet – oversikt og formål |
| `dokumentstruktur_id_konvensjon.md` | Regler for dokument-ID, filnavn, metadata og YAML-header |
| `mappeoversikt.md`                | Oversikt over struktur og mappehierarki i GitHub/Dropbox |
| `systemintegrasjon_dokumentstruktur.mmd` | Diagram over hvordan dokumentstruktur integreres med andre systemer |
| `ymal/`                            | YAML-filer for validering av ID, metadata og versjonslogg |
| *(planlagt)* `metadata_register.xlsx` | Oversikt over metadatafelt for dokumentasjon og revisjon |
| *(planlagt)* `dokumentlogg_oversikt.md` | Liste over aktive, arkiverte og godkjente styringsdokumenter |
| *(valgfritt)* `eksempler/`         | Eksempelfiler med korrekt navn og struktur |

---

## 🗂️ Dropbox: Mappeoversikt og struktur

### 📁 00–09 og 99 – Hovedmapper og undermapper

#### `00-Start-Here`
- *(Ingen undermapper dokumentert)*

#### `01-Business-Development`
- `01-Strategy-and-Market-Analysis`
- `02-Customer-Segments-and-Leads`
- `03-Sales-Pitches-and-Materials`
- `04-Investor-Relations`
- `05-Partner-Opportunities`
- `06-OKRs-and-Initiatives`

#### `02-Technology-Development`
- `01-Architecture-and-Design`
- `02-AI-and-Agent-Development`
- `03-Integrations-and-APIs`
- `04-Testing-and-Prototyping`
- `05-GitHub-Documentation-Sync`
- `06-Roadmap-and-Milestones`

#### `03-Company-Operations`
- `01-Org-Structure-and-Roles`
- `02-HR-and-Contracts`
- `03-Financials-and-Budget`
- `04-Governance-and-Board`
- `05-Legal-and-Compliance`

#### `04-TechOps-ServiceDelivery`
- `01-Customer-Support`
- `02-Service-Documentation`
- `03-Incident-and-Change-Management`
- `04-Operations-Metrics`
- `05-Customer-Onboarding`

#### `05-ISO-Standards`
- `01-Information-Security`
- `02-Quality-Management`
- `03-Records-Management`
- `04-Environmental-Management`
- `05-Risk-Management`
- `06-Data-Quality-for-AI`
- `07-Templates-and-Logs`

#### `06-Projects`
- `01-Internal`
- `02-Client-Projects`

#### `07-Vendors-and-Partners`
- `01-Consultants`
- `02-Technology-Partners`
- `03-Legal-and-Agreements`
- `04-Vendor-Selection-Criteria`

#### `08-Systems-and-Integrations`
- *(Ingen undermapper dokumentert)*

#### `09-Documentation-Templates`
- `01-Documentstructure`
- `02-Metadata`
- `03-Templates`
- `04-Metoder-og-modeller`

#### `99-Shared-and-Archive`
- `01-Temp-and-Drafts`
- `02-Shared-With-Partners`
- `03-Archived-Projects`
- `04-Old-Versions-and-Backups`

---

## 🧾 Relevante ISO-standarder

| Standard           | Relevans |
|--------------------|----------|
| **ISO 15489-1:2016** | Records management – Concepts and principles |
| **ISO 30301:2019**   | Management systems for records – Requirements |
| **ISO 27001:2022**   | ISMS – Krav til dokumentkontroll og sporbarhet |
| **ISO 9001:2015**    | Kvalitetsledelse – Versjonsstyring og revisjon |
| **ISO 19475:2021**   | Dokumentlagring og uthenting |

---

📁 **Plassering Dropbox:**  
`/NextGenio-plattform-09-Documetations-01-Documentstructure/dokumentstruktur_policy.md`

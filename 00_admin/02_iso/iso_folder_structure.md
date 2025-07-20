# 📘 Mappestruktur for `02_iso/` – ISO-standarder i NextGenio

**Dokument-ID:** NG-ISO-STR-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-20  
**Plassering:** `/00_admin/02_iso/iso_folder_structure.md`  
**Dropbox:** `NextGenio-plattform/05-ISO-Standards/`  
**Eier:** Henrik Strand – Kvalitetsleder

---

## 🎯 Formål
Denne mappen inneholder alle ISO-relaterte dokumenter, vurderinger, maler og metadata som benyttes i NextGenio for å oppfylle krav i ISO 9001, 27001, 15489, 30301 og 19475. 

Strukturen skal være:
- Sporbar og etterprøvbar
- Egnet for revisjon og compliance
- Agentvennlig og metadata-styrt
- I tråd med krav i dokumentpolicy og godkjenning_policy

---

## 🗂️ Mappestruktur og innhold

```plaintext
02_iso/
├── 01_summaries/               ← 📘 Sammenfatninger av ISO-standarder
├── 02_structure_control/       ← 🗂️ Strukturkontroll, policy og revisjon
├── 03_implementation_logs/     ← ✅ ISO-registrering, tiltak og loggføring
├── 04_templates/               ← 🧩 Maler for ISO-dokumentasjon
└── 05_metadata/                ← 📊 Metadata, navnekonvensjon og eksempler
```

---

### 📁 01_summaries/
Forklarer formål, struktur og nøkkelpunkter i ISO-standardene som er relevante for NextGenio. Disse benyttes til forståelse, agenttrening og dokumentasjon.

### 📁 02_structure_control/
Inneholder vurderinger, sjekklister og integrasjonsdiagrammer relatert til dokumentstrukturens samsvar med ISO. Vurderinger er koblet til både `policy_register.md` og `dokumentpolicy.md`.

### 📁 03_implementation_logs/
Logger implementerte tiltak, med `iso_register.md` og `versionslogg.yaml` som kjernefiler. Gir sporbarhet, historikk og grunnlag for revisjon.

### 📁 04_templates/
Standardiserte malfiler for ISO-dokumentasjon, sammenfatning, revisjon og versjonslogg. Pålagt brukt ved all ny opprettelse av ISO-relaterte dokumenter.

### 📁 05_metadata/
Definerer hvordan metadata skal håndteres, hvilke felt som kreves og hvordan dokumenter skal struktureres med YAML-header. Støtter AI- og søkefunksjoner i Supabase og GitHub.

---

## 🔐 Tilgang og roller

| Mappe                    | Tilgangsnivå      | Godkjenningsansvarlig     |
|--------------------------|-------------------|----------------------------|
| 01_summaries/            | Åpen for lesing   | Kvalitetsleder             |
| 02_structure_control/    | Begrenset         | Kvalitetsleder + Compliance|
| 03_implementation_logs/  | Kun redigerbare av autoriserte | Kvalitetsleder |
| 04_templates/            | Lesetilgang alle  | Dokumentansvarlig          |
| 05_metadata/             | Begrenset skrivetilgang | Systemansvarlig       |

---

## 📄 Dokumentkontroll

| Felt             | Innhold                           |
|------------------|-----------------------------------|
| Opprettet av     | Henrik Strand                     |
| Godkjent av      | [Navn] + [Navn]                   |
| Revisjonsintervall | 12 måneder                      |
| Versjon          | 1.0                               |
| Versjonslogg     | Registrert i `versionslogg.yaml`  |

---

> 🔁 Denne README-filen er en del av NextGenios styringssystem og må holdes oppdatert ved alle endringer i mappestruktur eller policy.

# 🏛️ TOGAF Framework – Enterprise Architecture i NextGenio

**Dokument-ID:** NG-FRM-EA-TOGAF-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-21  
**Plassering:** `/00_admin/03_frameworks/01_enterprise_architecture/togaf_framework.md`  
**Eier:** Arkitekturansvarlig  

---

## 🎯 Formål

Dette dokumentet beskriver bruken av **TOGAF** (The Open Group Architecture Framework) som sentralt rammeverk for **Enterprise Architecture** i NextGenio-plattformen. TOGAF gir strukturert støtte for planlegging, utvikling, implementering og styring av helhetlig systemarkitektur.

---

## 🧱 Kjernekomponenter i TOGAF

TOGAF består av følgende hoveddeler:

| Komponent                | Beskrivelse |
|--------------------------|-------------|
| **ADM (Architecture Development Method)** | Iterativ metode for utvikling av arkitektur i faser A–H |
| **Architecture Content Framework** | Standard for hva arkitekturartefakter skal inneholde |
| **Enterprise Continuum** | Strukturerer gjenbruk av modeller og arkitekturressurser |
| **Reference Models (TRM & III-RM)** | Teknologiske og integrasjonsmessige referansemodeller |

---

## 🔁 ADM-syklusen – faser

```plaintext
          A — Architecture Vision
         / \
        H   B — Business Architecture
       /     \
      G       C — Information Systems Architecture
       \     /
        F   D — Technology Architecture
         \ /
          E — Opportunities & Solutions
             ↓
         Requirements Management (kontinuerlig)
```

| Fase  | Innhold |
|-------|---------|
| A     | Definerer visjon, mål, scope og stakeholders |
| B     | Modellering og utvikling av forretningsarkitektur |
| C     | Applikasjon og datamodeller |
| D     | Infrastruktur og teknologi |
| E     | Integrert veikart for endring |
| F     | Migrasjonsplaner og risikovurdering |
| G     | Governance og arkitekturoppfølging |
| H     | Kontinuerlig forbedring og tilbakemating |
| RM    | Krever og styrer endringer gjennom hele syklusen |

---

## 🧩 Bruk i NextGenio

TOGAF benyttes som **overordnet struktur** for:

- Kartlegging av arkitekturlag: Business, Data, Application, Technology
- Etablering av veikart og roadmap for plattformen
- Støtte for utvikling av AI-agenter og agentansvar
- Harmonisering med ISO-standarder og dokumentpolicyer

TOGAF kobles tett mot:
- 📐 C4 Model – for systemvisualisering
- 🧠 OKR og Business Capability Map – i fase B
- 📋 ISO 9001 og 27001 – i fase G og H
- 🔄 Supabase og devcontainer-oppsett – i fase D og E

---

## 📌 Relaterte ressurser

- [TOGAF® Standard, Version 9.2](https://www.opengroup.org/togaf)
- Intern NextGenio-ressurs: `/docs/architecture/togaf.mmd`
- Koblede rammeverk: `c4_model.md`, `business_capability_map.md`, `iso_9001.md`

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                  |
|------------------|-------------------------------------------|
| Opprettet av     | Henrik Strand                             |
| Revidert dato    | 2025-07-21                                |
| Versjon          | 1.0                                       |
| Status           | Aktiv                                     |
| GitHub-plassering| `/00_admin/03_frameworks/01_enterprise_architecture/` |

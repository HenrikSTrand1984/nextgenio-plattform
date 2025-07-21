# 🧩 ArchiMate Framework – Modellering av Enterprise Architecture i NextGenio

**Dokument-ID:** NG-FRM-EA-ARCHIMATE-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-21  
**Plassering:** `/00_admin/03_frameworks/01_enterprise_architecture/archimate_framework.md`  
**Eier:** Arkitekturansvarlig  

---

## 🎯 Formål

ArchiMate er et standardisert notasjonsspråk utviklet av The Open Group for modellering av **Enterprise Architecture**. I NextGenio brukes ArchiMate som komplement til TOGAF og C4 for å beskrive relasjoner mellom forretning, applikasjoner og teknologi på tvers av systemet.

---

## 🧱 ArchiMate-lag og domener

ArchiMate deler EA i tre primære lag:

| Lag             | Domener                   | Eksempel |
|------------------|---------------------------|----------|
| **Business Layer** | Aktiviteter, prosesser, aktører  | Tjenesteleveranse, brukerstøtte, kundegrensesnitt |
| **Application Layer** | Applikasjoner og systemer | Supabase, API-tjenester, OpenAI-integrasjon |
| **Technology Layer** | Infrastruktur og plattformer | Docker, VS Code Devcontainer, databaselag |

---

## 🔄 Kobling med TOGAF og NextGenio

- ArchiMate gir **grafisk fremstilling** av arkitekturen som utvikles i TOGAF ADM
- Brukes i **fase B–D** i TOGAF (Business, Information Systems og Technology Architecture)
- Supplerer C4 ved å beskrive **forretningsmessige avhengigheter og komponentrelasjoner**

---

## 🛠️ Verktøy som støtter ArchiMate

- [Archi](https://www.archimatetool.com/) – Open source modellverktøy
- BizzDesign – Kommersiell EA-suite med dypt TOGAF-integrert støtte
- Draw.io / Mermaid – For enklere diagrammer i GitHub

---

## 🧩 Typiske modeller i NextGenio

- Forretningsprosesskart for agenter
- Applikasjonskart mellom Supabase, API-er og agenter
- Teknologikart for containerstruktur og DevOps-miljø
- ISO-relasjoner (kvalitet, sikkerhet, dokumentstyring)

---

## 📎 Relaterte filer

- `togaf_framework.md`
- `supabase_forklaring.md`
- `/docs/architecture/archimate_business_layer.drawio`
- `/docs/architecture/archimate_technology_layer.drawio`

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                  |
|------------------|-------------------------------------------|
| Opprettet av     | Henrik Strand                             |
| Revidert dato    | 2025-07-21                                |
| Versjon          | 1.0                                       |
| Status           | Aktiv                                     |
| GitHub-plassering| `/00_admin/03_frameworks/01_enterprise_architecture/` |

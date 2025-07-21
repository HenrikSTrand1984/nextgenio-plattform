# 🧠 Business Capability Mapping – Strukturering av forretningskapabiliteter i NextGenio

**Dokument-ID:** NG-FRM-EA-CAPMAP-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-21  
**Plassering:** `/00_admin/03_frameworks/01_enterprise_architecture/business_capability_map.md`  
**Eier:** Arkitekturansvarlig  

---

## 🎯 Formål

Business Capability Mapping (BCM) brukes i NextGenio for å kartlegge **hva organisasjonen kan gjøre**, uavhengig av struktur, prosesser eller teknologi. Det gir et stabilt rammeverk for utvikling, prioritering og organisering av forretningsarkitekturen.

---

## 🧱 Hva er en kapabilitet?

En kapabilitet representerer **evnen til å oppnå et definert utfall** gjennom en kombinasjon av mennesker, prosesser, teknologi og informasjon.

Eksempler i NextGenio:
- Kvalitetsstyring
- Dokumenthåndtering
- Agentoppsett
- Dataintegrasjon
- Policy-governance
- Kundestøtte og leveranse

---

## 🗺️ Kartleggingsstruktur

| Nivå | Betegnelse                 | Eksempel fra NextGenio |
|------|----------------------------|-------------------------|
| 1    | Domene                     | Informasjonsstyring     |
| 2    | Kapabilitet                | Dokumentkontroll        |
| 3    | Underkapabilitet           | Versjonshåndtering, tilgangsstyring |

---

## 🧩 Bruksområder i NextGenio

- **Strategisk prioritering** – identifisere gap mellom nåværende og ønsket evne
- **Agent-arkitektur** – mappe hvilke agenter som støtter hvilke kapabiliteter
- **DevOps-roadmap** – koble utviklingsaktiviteter til kapabilitetsmål
- **Samsvar** – relatere kapabiliteter til ISO-krav (9001, 27001, 30301)

---

## 📊 Visualisering

Kapabilitetskartet visualiseres ofte som et hierarkisk rutenett eller fargekodet matrise. Dette lagres i:

- `/docs/architecture/business_capability_map.drawio`
- Kan også vises med Mermaid (`capability_map.mmd`)

---

## 🔄 Relasjoner

| Relasjonstype | Kobles til |
|---------------|------------|
| Kapabilitet ↔ ISO-krav | ISO 9001, 27001 |
| Kapabilitet ↔ Agent     | agent_register.md |
| Kapabilitet ↔ Teknologi | Supabase, OpenAI, auth-system |

---

## 📎 Relaterte filer

- `togaf_framework.md`
- `iso_9001_quality/README.md`
- `agent_register.md`
- `/docs/architecture/business_capability_map.drawio`

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                  |
|------------------|-------------------------------------------|
| Opprettet av     | Henrik Strand                             |
| Revidert dato    | 2025-07-21                                |
| Versjon          | 1.0                                       |
| Status           | Aktiv                                     |
| GitHub-plassering| `/00_admin/03_frameworks/01_enterprise_architecture/` |

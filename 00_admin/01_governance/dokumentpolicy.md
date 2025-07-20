# 📘 Dokumentpolicy – Retningslinjer for dokumentforvaltning i NextGenio

**Dokument-ID:** NG-GOV-DOC-0001  
**Versjon:** 1.1  
**Status:** Aktiv  
**Dato:** 2025-07-20  
**Plassering:** `/00_admin/01_governance/dokumentpolicy.md`  
**Dropbox / SharePoint:** `NextGenio-plattform/00_Admin/01_Governance/`  
**Eier:** Henrik Strand – Kvalitetsleder

---

## 🎯 Formål

Dette dokumentet definerer prinsipper og retningslinjer for strukturert og kontrollert dokumentforvaltning i NextGenio.

Policyen sikrer:

- 📎 Samsvar med ISO-standarder (15489, 30301, 27001, 9001)
- 🏷️ Riktig klassifisering, versjonering og arkivering
- 🔐 Kontrollert tilgang og ansvarlig eierskap
- 🤖 Gjenbruk og agenttilgang til strukturert informasjon

---

## 📂 Dokumentklasser (utvalg)

| Klasse              | Beskrivelse                                      | Eksempel                            |
|---------------------|--------------------------------------------------|-------------------------------------|
| Policy              | Overordnede føringer og prinsipper               | dokumentpolicy.md                   |
| Prosedyre           | Beskriver gjennomføring av definerte prosesser   | audit_procedure.md                  |
| Mal (template)      | Strukturert utgangspunkt for nye dokumenter      | procedure_template.md               |
| Rapport             | Utdata og vurderinger fra aktivitet eller analyse| audit_report_template.md            |
| Logg / YAML         | Strukturert loggfil i YAML-format                | audit_log.yaml                      |
| Rollebeskrivelse    | Beskrivelse av ansvar, myndighet og oppgaver     | kvalitetsleder.md                   |

---

## 🧱 Navnestandard

- Filnavn: **small_case_with_underscores.md**
- Eksempel: `audit_checklist_template.md`
- Filtyper: `.md`, `.yaml`, `.drawio`, `.svg`, `.xlsx`, `.json`

---

## 🔁 Versjonering og revisjon

- Alle dokumenter skal ha **versjon, dato, status og dokument-ID** i toppen
- Endringer loggføres i `versionslogg.yaml`
- Historikk arkiveres ved større revisjoner (v2.0, v3.0 etc.)

---

## 🧑‍🤝‍🧑 Ansvar og roller

- **Eier** defineres i toppen av dokumentet
- **Godkjent av** må signeres av minimum 2 ansvarlige (f.eks. Kvalitetsleder + Daglig leder)
- RACI-matrisen brukes for alle dokumentklasser

---

## 🔐 Tilgang og rettigheter

| Nivå              | Beskrivelse                                 |
|-------------------|---------------------------------------------|
| Åpen              | Synlig for alle med tilgang til repoet       |
| Begrenset         | Kun for utvalgte roller / mapper             |
| Strengt konfidensielt | Kryptert og/eller kun tilgjengelig via godkjenning |

---

## 📄 Dokumentkontroll

| Felt               | Innhold                                                      |
|--------------------|--------------------------------------------------------------|
| Opprettet av       | Henrik Strand                                                |
| Godkjent av        | Henrik Strand, [navn 2]                                      |
| Revidert dato      | 2025-07-20                                                   |
| Versjonslogg       | Registrert i `versionslogg.yaml`                             |

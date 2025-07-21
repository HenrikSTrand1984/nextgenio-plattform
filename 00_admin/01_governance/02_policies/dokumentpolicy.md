# 📘 Dokumentpolicy – Retningslinjer for dokumentforvaltning i NextGenio

**Dokument-ID:** NG-GOV-DOC-0001  
**Versjon:** 1.2  
**Status:** Aktiv  
**Dato:** 2025-07-21  
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

> 📂 *Se også:* `mappepolicy.md` for struktur og navnestandarder for mapper.

---

## 📂 Dokumentklasser (utvalg)

| Klasse              | Beskrivelse                                      | Eksempel                            | Malplassering |
|---------------------|--------------------------------------------------|-------------------------------------|----------------|
| Policy              | Overordnede føringer og prinsipper               | dokumentpolicy.md                   | 05_templates/04_policies/ |
| Prosedyre           | Beskriver gjennomføring av definerte prosesser   | audit_procedure.md                  | 05_templates/03_iso/ |
| Mal (template)      | Strukturert utgangspunkt for nye dokumenter      | procedure_template.md               | 05_templates/ |
| Rapport             | Utdata og vurderinger fra aktivitet eller analyse| audit_report_template.md            | 05_templates/06_examples/ |
| Logg / YAML         | Strukturert loggfil i YAML-format                | audit_log.yaml                      | 05_templates/05_yaml/ |
| Rollebeskrivelse    | Beskrivelse av ansvar, myndighet og oppgaver     | kvalitetsleder.md                   | 05_templates/07_agents/ |

---

## 🧱 Navnestandard

- Filnavn: **small_case_with_underscores.md**
- Eksempel: `audit_checklist_template.md`
- Filtyper: `.md`, `.yaml`, `.drawio`, `.svg`, `.xlsx`, `.json`

---

## 🧾 YAML-metadata – minstekrav

Alle dokumenter skal inneholde følgende YAML-header i toppen:

```yaml
dokument_id: NG-XXX-XXX-000X
versjon: 1.0
status: aktiv
dato: YYYY-MM-DD
eier: Navn / Rolle
```

---

## 🔁 Versjonering og revisjon

- Alle dokumenter skal ha **versjon, dato, status og dokument-ID** i toppen
- Endringer loggføres i `/00_admin/01_governance/versionslogg.yaml`
- Historikk arkiveres ved større revisjoner:
  - Mappes under `/00_admin/01_governance/_archive/`
  - Navngis som `filnavn_v1.0_archived.md`

---

## 🧑‍🤝‍🧑 Ansvar og roller

- **Eier** defineres i toppen av dokumentet
- **Godkjent av** må signeres av minimum 2 ansvarlige (f.eks. Kvalitetsleder + Daglig leder)
- RACI-matrisen brukes for alle dokumentklasser

---

## 🔐 Tilgang og rettigheter

| Nivå                  | Beskrivelse                                                |
|------------------------|------------------------------------------------------------|
| Åpen                  | Synlig for alle med tilgang til repoet                     |
| Begrenset             | Kun for utvalgte roller / mapper                           |
| Strengt konfidensielt | Kryptert og/eller kun tilgjengelig via godkjenning         |

---

## 📚 Relaterte dokumenter

- `mappepolicy.md` – Struktur og navnestandarder for mapper
- `policy_register.md` – Oversikt over aktive policyer
- `godkjenning_policy.md` – Retningslinjer for godkjenning og eierskap
- `README.md` i `05_templates/` – Oversikt over maler og standarder

---

## 📄 Dokumentkontroll

| Felt               | Innhold                                                      |
|--------------------|--------------------------------------------------------------|
| Opprettet av       | Henrik Strand                                                |
| Godkjent av        | Henrik Strand, [navn 2]                                      |
| Revidert dato      | 2025-07-21                                               |
| Versjonslogg       | Registrert i `versionslogg.yaml`                             |

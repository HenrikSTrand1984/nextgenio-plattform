# ✅ Godkjenningspolicy – Retningslinjer for dokumentgodkjenning i NextGenio

**Dokument-ID:** NG-GOV-DOC-0002  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-20  
**Plassering:** `/00_admin/01_governance/godkjenning_policy.md`  
**Dropbox / SharePoint:** `NextGenio-plattform/00_Admin/01_Governance/`  
**Eier:** Henrik Strand – Kvalitetsleder

---

## 🎯 Formål

Denne policyen etablerer retningslinjer for **godkjenning av dokumenter** i NextGenio. Målet er å sikre tydelig eierskap, kvalitetskontroll og sporbarhet i samsvar med ISO 9001, ISO 15489 og intern dokumentpolicy.

---

## 📄 Hva skal godkjennes?

Alle dokumenter klassifisert som:

- 📘 Policy
- 📝 Prosedyre
- 📑 Rapport / revisjonsutdata
- 📂 Rollebeskrivelse
- 📋 Protokoller og loggfiler (yaml)

...må gjennom **minst to-trinns godkjenning** før de merkes som "Aktiv".

---

## 🧾 Godkjenningsprosess

| Trinn | Ansvarlig rolle        | Beskrivelse                                      |
|-------|-------------------------|--------------------------------------------------|
| 1     | Dokumenteier            | Utarbeider og foreslår dokumentet                |
| 2     | Kvalitetsleder          | Kvalitetssikrer innhold og struktur              |
| 3     | [Sekundær godkjenner]   | Operativ/strategisk godkjenning av gyldighet     |
| 4     | Systemansvarlig (AI)    | Registrerer dokumentet i `versionslogg.yaml`     |

---

## 🖊️ Metadata og signaturkrav

Hvert dokument skal inneholde:

- **Opprettet av**: Navn og rolle
- **Godkjent av**: Minst 2 godkjennere (navn og rolle)
- **Revisjonsdato**: Sist oppdatert
- **Versjonslogg**: Referanse til `versionslogg.yaml`

Signatur kan utføres via:
- Digital Git-commit signering
- Versjonshistorikk og godkjenningslogg i YAML

---

## 📋 Unntak

- Maler og hjelpefiler (f.eks. templates) trenger **kun én godkjenner**
- Kladd-statusdokumenter må være tydelig merket med `Status: Under utvikling`

---

## 🧠 Agentstøtte

AI-agenter med riktige rettigheter skal:
- Sjekke godkjenningsstatus før bruk av dokument
- Automatisk flagge manglende eller foreldet godkjenning

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                              |
|------------------|-------------------------------------------------------|
| Opprettet av     | Henrik Strand                                        |
| Godkjent av      | Henrik Strand, [navn 2]                              |
| Revidert dato    | 2025-07-20                                           |
| Versjonslogg     | Registrert i `versionslogg.yaml`                     |

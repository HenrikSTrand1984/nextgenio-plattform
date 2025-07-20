# 📘 Policy: Godkjenning av dokumenter i NextGenio

**Dokument-ID:** NG-GOV-POLICY-GODKJENNING-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-19  
**Dokumenteier:** Henrik Strand – Kvalitetsleder, NextGenio  
**Plassering GitHub:** /admin/governance/godkjenning_policy.md  
**Plassering Dropbox:** /NextGenio-plattform/admin/governance/godkjenning_policy.md  

---

## 🎯 Formål

Definere krav og praksis for **godkjenning av dokumenter** i NextGenio, slik at all dokumentasjon er sporbar, etterprøvbar og autorisert i tråd med ISO 9001, ISO 15489 og interne dokumentpolicyer.

---

## 🧭 Hva omfattes av denne policyen?

Denne policyen gjelder for:

- Alle filer med status `Aktiv` i GitHub- eller Dropbox-strukturen
- Dokumenter underlagt versjonskontroll (`versjonslogg.yaml`)
- Alle maler, policyer, prosedyrer og rollebeskrivelser

---

## ✅ Krav til godkjenning

| Type dokument            | Minstekrav for godkjenning       | Kommentar                          |
|--------------------------|----------------------------------|------------------------------------|
| Policyfiler              | Min. 2 personer                  | Én må være Kvalitetsleder          |
| Maler (`templates/`)     | Én fagansvarlig + kvalitetsleder | Skal følges av brukerveiledning    |
| Rollebeskrivelser        | Fagansvarlig for rollen + Henrik Strand | RACI-ansvar må defineres     |
| Operasjonelle dokumenter | Én eier + én validator           | Kan være AI-agent + menneske       |
| Agentbeskrivelser        | Utvikler + kvalitetsleder        | Versjonsføres og kobles til YAML   |

---

## 🧩 Godkjenningsroller (RACI)

| Rolle               | R | A | C | I |
|---------------------|---|---|---|---|
| Dokumenteier        | X |   |   |   |
| Kvalitetsleder      |   | X |   |   |
| AI-assistent        |   |   | X |   |
| Ledelse / PMO       |   |   |   | X |

> Alle endelige godkjenninger loggføres i `versjonslogg.yaml` og skal signeres med navn og dato.

---

## 📋 Prosess for godkjenning

1. **Utkast opprettes** og lagres i GitHub/DROPBOX som "Under utvikling"
2. **Gjennomgang av dokumenteier**
3. **Godkjenning av minst én kvalitetsansvarlig**
4. **Status endres til "Aktiv"**
5. **Dokument og metadata legges inn i `versjonslogg.yaml`**

---

## 🔒 Krav til sporbarhet

- All godkjenning skal være **verifiserbar** gjennom:
  - Dokument-ID og versjon
  - Tidsstempel (godkjent dato)
  - Signatur (navn eller AI-agent)
- Supabase brukes som støtte for autentisering og arkiv

---

## 📚 Relaterte dokumenter

- `dokumentpolicy.md`  
- `readme_policy.md`  
- `versjonslogg.yaml`  
- `policy_register.md`  
- `rollebeskrivelser/`  
- `readme_template.md`

---

## 📄 Dokumentkontroll

| Felt           | Innhold                                             |
|----------------|-----------------------------------------------------|
| Dokument-ID    | NG-GOV-POLICY-GODKJENNING-0001                      |
| Versjon        | 1.0                                                 |
| Status         | Aktiv                                               |
| Opprettet      | 2025-07-19                                          |
| Sist revidert  | 2025-07-19                                          |
| Godkjent dato  | 2025-07-19                                          |
| Dokumenteier   | Henrik Strand – Kvalitetsleder, NextGenio           |
| Godkjent av    | Henrik Strand & AI Assistant                        |
| Logg           | Registrert i `versjonslogg.yaml` og Supabase        |

---

## 📂 Plassering

| Miljø               | Sti                                                                 |
|---------------------|---------------------------------------------------------------------|
| GitHub              | `/admin/governance/godkjenning_policy.md`                           |
| Dropbox / SharePoint| `/NextGenio-plattform/admin/governance/godkjenning_policy.md`       |

---

🛡️ *Alle dokumenter i NextGenio må følge denne policyen før de kan anses som gyldige og autoritative.*


# 📘 Policy: Dokumentforvaltning i NextGenio

**Dokument-ID:** NG-GOV-POLICY-DOK-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-19  
**Dokumenteier:** Henrik Strand – Kvalitetsleder, NextGenio  
**Plassering GitHub:** /admin/governance/dokumentpolicy.md  
**Plassering Dropbox/SharePoint:** /NextGenio-plattform/admin/governance/dokumentpolicy.md  

---

## 🎯 Formål

Denne policyen definerer prinsipper og regler for **strukturert dokumentforvaltning** i NextGenio. Målet er å sikre **kvalitet, sporbarhet, tilgang og etterprøvbarhet** i henhold til relevante ISO-standarder og interne krav.

---

## 🧱 Omfang

Gjelder for alle:

- Prosjektdokumenter
- Maler og policyer
- Agentbeskrivelser og YAML-konfigurasjoner
- README.md-filer og tilhørende guider
- Repositorier og Dropbox/SharePoint-strukturer

---

## 🧭 Dokumentklasser

| Klasse             | Beskrivelse                             | Eksempler                          |
|--------------------|------------------------------------------|------------------------------------|
| Styrende dokument  | Regler og policy som må følges           | `dokumentpolicy.md`, `readme_policy.md` |
| Operasjonelt       | Bruksdokumenter, prosesser, maler        | `readme_template.md`, `metoder/`   |
| Prosjektspesifikt  | Dokumentasjon knyttet til ett prosjekt   | `supabase_setup_log.md`            |
| Agentspesifikt     | YAML, funksjonsfiler, use case-dokumenter| `agent_usecase_kvalitetsleder.md`  |
| Generert output    | Rapporter, eksporterte diagrammer o.l.   | `output/*.pdf`, `output/*.drawio`  |

---

## 🔐 Tilgangsstyring

| Nivå        | Rettigheter                         | Eksempel                        |
|-------------|-------------------------------------|---------------------------------|
| Eier        | Full tilgang og endringsansvar      | Henrik Strand, prosjekteier     |
| Redaktør    | Kan redigere og oppdatere           | AI-assistenter                  |
| Lesetilgang | Kun visning                         | Andre prosjektmedlemmer         |
| Ekstern     | Begrenset tilgang (ShareLink)       | Kunde, ekstern revisor          |

---

## 🔄 Versjonskontroll

- Alle styrende dokumenter skal:
  - Ha dokument-ID, versjon, status, dato og eier
  - Versjonsføres i `versjonslogg.yaml`
  - Kun endres etter godkjenning i henhold til `godkjenning_policy.md`
- Endringer skal være sporbare i både GitHub-logg og Supabase-logg

---

## 🧩 Metadata og strukturkrav

Alle dokumenter skal inneholde:

- Topptekst med: Dokument-ID, versjon, status, dato, eier
- Bunnseksjon med: Dokumentkontroll og plassering
- Lagring i **både GitHub og Dropbox/SharePoint** med speilstruktur
- README.md i hver mappe som forklarer innhold og bruk

---

## 🛡️ Standarder og rammeverk

| Standard     | Bruksområde                         |
|--------------|--------------------------------------|
| ISO 9001     | Dokumentert informasjon og kvalitet |
| ISO 15489    | Dokumentstyring og metadata         |
| ISO 27001    | Informasjonssikkerhet og tilgang    |
| ISO 30301    | Struktur og informasjonsstyring     |

---

## 📚 Relaterte dokumenter

- `readme_policy.md`  
- `godkjenning_policy.md`  
- `dokumentstruktur_policy.md`  
- `versjonslogg.yaml`  
- `policy_register.md`  
- `readme_template.md`

---

## 📄 Dokumentkontroll

| Felt           | Innhold                                             |
|----------------|-----------------------------------------------------|
| Dokument-ID    | NG-GOV-POLICY-DOK-0001                              |
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

| Miljø               | Sti                                                                  |
|---------------------|----------------------------------------------------------------------|
| GitHub              | `/admin/governance/dokumentpolicy.md`                                |
| Dropbox / SharePoint| `/NextGenio-plattform/admin/governance/dokumentpolicy.md`            |

---

🛡️ *Denne policyen er bindende for all dokumentforvaltning i NextGenio-plattformen og skal være kjent for alle som jobber med utvikling, ledelse og AI-agenter.*


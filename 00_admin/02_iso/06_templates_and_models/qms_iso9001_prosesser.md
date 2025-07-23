# 📘 ISO 9001:2015 – Prosess- og Prosedyreregister (Norsain QMS)

**Dokument-ID:** NTG-QMS-CORE-0001  
**Versjon:** 0.1  
**Status:** Struktur / Klar for utfylling  
**Dato:** 2025-07-23  
**Plassering:** `/00_admin/02_iso/06_templates_and_models/qms_iso9001_prosesser.md`  
**Eier:** Kvalitetsleder / Norsain Technology Group  

---

## 🎯 Formål

Dette dokumentet definerer **rammestrukturen** for alle prosesser, prosedyrer og dokumenterte krav i henhold til **NS-EN ISO 9001:2015**.  
Hensikten er å sikre at Norsain har et levende kvalitetssystem, hvor alle deler av standarden er implementert, ansvarliggjort og koblet til Supabase og ClickUp for kontinuerlig forbedring.

Alle prosessdokumenter og prosedyrer skal **lagres og versjonstyres i Supabase SQL-database**, og gjøres tilgjengelig for kvalitetssystemets agentarkitektur.

---

## 🧱 Oversikt – Obligatoriske QMS-prosesser iht. ISO 9001

| Punkt | Prosess / kravområde                             | Filnavn                          | Status        | Agentansvar            |
|-------|--------------------------------------------------|----------------------------------|----------------|------------------------|
| 4.1   | Forstå organisasjonens kontekst                  | `qms_041_kontekst.md`            | Skjelett       | Strategy Agent         |
| 4.2   | Interessentbehov og -forventninger               | `qms_042_interessenter.md`       | Skjelett       | Strategy Agent         |
| 4.4   | Systemets prosesser (prosesskart)                | `qms_044_prosesskart.md`         | Struktur       | Quality Manager Agent  |
| 5.1   | Lederskap og engasjement                         | `qms_051_lederskap.md`           | Skjelett       | CEO Agent              |
| 6.1   | Risiko og muligheter                             | `qms_061_risikoanalyse.md`       | Utkast         | Risk Agent             |
| 6.2   | Kvalitetsmål og plan                             | `qms_062_kvalitetsmaal.md`       | Skjelett       | Quality Manager Agent  |
| 7.1   | Ressurser                                         | `qms_071_ressurser.md`           | Mangler        | HR Agent               |
| 7.2   | Kompetanse                                       | `qms_072_kompetanse.md`          | Startet        | Quality Manager Agent  |
| 7.5   | Dokumentstyring                                  | `qms_075_dokumentstyring.md`     | Skjelett       | Compliance Agent       |
| 8.1   | Operasjonell planlegging og styring              | `qms_081_operasjon.md`           | Mangler        | Operations Agent       |
| 8.2   | Håndtering av kundekrav                          | `qms_082_kundekrav.md`           | Skjelett       | Customer Agent         |
| 8.3   | Utforming og utvikling (R&D)                     | `qms_083_designutvikling.md`     | Delvis         | Innovation Agent       |
| 8.4   | Kontroll av innkjøp / leverandører               | `qms_084_innkjop.md`             | Mangler        | Supply Chain Agent     |
| 8.5   | Produksjon og tjenesteleveranse                  | `qms_085_leveranse.md`           | Mangler        | Delivery Agent         |
| 8.7   | Kontroll av ikke-samsvarende tjenester/produkter | `qms_087_avvikskontroll.md`      | Skjelett       | QA Agent               |
| 9.1   | Overvåking og måling                             | `qms_091_maling_og_data.md`      | Mangler        | KPI Agent              |
| 9.2   | Intern revisjon                                  | `qms_092_revisjon.md`            | Mangler        | Audit Agent            |
| 9.3   | Ledelsens gjennomgang                            | `qms_093_ledelsesgjennomgang.md` | Mangler        | CEO Agent              |
| 10.1–3| Forbedring og avvikshåndtering                   | `qms_10x_forbedring.md`          | Skjelett       | Improvement Agent      |

---

## 🛠️ Strukturmal for hver prosessfil

Hver prosess skal følge denne standardstrukturen i sin `.md`-fil:

```markdown
# 📄 Prosessnavn: [ISO-krav: x.x]

**Dokument-ID:** NTG-QMS-XXXX-000x  
**Versjon:** 0.1  
**Status:** [Skjelett / Under arbeid / Klar]  
**Dato:** [YYYY-MM-DD]  
**Eier:** [Agentnavn eller rolle]

---

## 🎯 Formål

## 📋 Anvendelsesområde

## 📥 Inndata / kravgrunnlag

## 🛠️ Beskrivelse av prosess

## 🔄 Prosesstrinn (evt. flyt-diagram i Mermaid)

## 🧑 Ansvar og roller

## 🧾 Tilknyttede prosedyrer og skjema

## 🗂️ Dokumentasjon og loggkrav

## 🧠 Agent-API eller Supabase-integrasjon (om aktuelt)
```

---

## 🔄 Supabase-integrasjon

Alle prosesser lagres som poster i tabellen `qms_prosesser` i Supabase. Eksempelstruktur:

```sql
CREATE TABLE qms_prosesser (
  id UUID PRIMARY KEY,
  iso_punkt TEXT,
  navn TEXT,
  dokument_id TEXT,
  agent_ansvar TEXT,
  status TEXT,
  versjon TEXT,
  filnavn TEXT,
  sist_oppdatert TIMESTAMP
);
```

Data oppdateres løpende av `Quality Manager Agent` og kan synkes til ClickUp for prosjektoppfølging og versjonskontroll.

---

## 📌 Neste steg

- Initialiser supabase-tabellen `qms_prosesser`
- Opprett `.md`-filer pr. ISO-punkt iht. oversikten
- Definer agentroller med ansvar
- Koble til ClickUp-liste for prosjektoppfølging

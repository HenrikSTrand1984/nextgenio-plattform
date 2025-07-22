# 🧱 Metodekart: Kobling mellom DTO-struktur og forsknings-/innovasjonsmetoder

**Dokument-ID:** NTG-FRM-DTOMAP-0001  
**Versjon:** 1.0  
**Status:** Aktiv (første versjon)  
**Dato:** 2025-07-22  
**Plassering:** `/00_admin/03_frameworks/04_quality_and_process/dto_metodekart.md`  
**Eier:** Henrik Strand / Norsain Technology Group  

---

## 🎯 Formål

Dette dokumentet beskriver hvordan definerte forsknings- og innovasjonsmetoder knyttes til komponenter i Norsains digitale tvilling-struktur (DTO). Det gjør det mulig å:

- Styre metodebruk basert på modenhet, risiko og prosessnivå
- Allokere riktige metoder til agentroller og KPI-strukturer
- Dynamisk anbefale metoder i beslutnings- og utviklingsløp

---

## 🧱 DTO-komponenter og metodetilknytning

| DTO-komponent              | Relevante metoder og koblinger                                        | Effekt og bruk                                                                 |
|----------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `twin.yaml.processes`      | DSR, PDCA, ISO 56002, TRIZ, FMEA                                       | Strukturerer innovasjons- og forbedringsprosesser                              |
| `twin.yaml.roles`          | Agentrolle-mapping, metodekart fra `agentrolle_metodekart.md`          | Knytter hver rolle til metodisk kapasitet og tilgang                           |
| `twin.yaml.kpi`            | Balanced Scorecard, OKR, Innovation Metrics, TRL-score                 | Måling av fremdrift og virkning i FoU / eksperimentelle løp                    |
| `twin.yaml.maturity_state` | TRL, SoSE, McKinsey 3 Horizons, Scenario Planning                      | Vurderer teknologiens eller prosessens utviklingstrinn                         |
| `twin.yaml.risk_profile`   | Foresight, PESTLE, SWOT, ALTAI, Real Options, Risk Matrix              | Evaluerer risiko/usikkerhet knyttet til metoder og teknologivalg               |
| `twin.yaml.impact_path`    | Theory of Change (ToC), OECD TIP, Impact Mapping                       | Visualiserer antatt virkningskjede fra innsats til effekt                      |
| `twin.yaml.knowledgebase`  | C-K Theory, DSR-resultater, ETRP-dokumentasjon, læring                 | Kunnskapsbank for tidligere hypoteser, forsøk og læring                        |

---

## 🧩 Eksempelbruk

**Scenario:**  
Et nytt teknologikonsept opprettes i DTO → status = TRL 3 + risiko = høy → DTO foreslår bruk av:

- `DSR` og `C-K Theory` for utforskning
- `FMEA` for risikostyring
- `ToC` for å modellere ønsket effekt
- `ETRP` for å dokumentere forskningsløpet
- Knytter til `Research Architect Agent` + `Ethics & Impact Agent`

---

## 🗂️ Plassering i tvillingfil

```yaml
twin.yaml:
  maturity_state:
    value: TRL_3
    linked_methods: [DSR, C-K Theory, FMEA, ETRP]
  risk_profile:
    type: HIGH_TECH_UNCERTAINTY
    mitigation_methods: [Foresight, SWOT, Real Options]
  impact_path:
    model: Theory_of_Change
    outcome_metrics: [Innovation Effectiveness Index, Adoption Ratio]
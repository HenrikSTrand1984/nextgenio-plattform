# 🤖 Metodekart: Agentroller og tilknyttede metoder

**Dokument-ID:** NTG-FRM-AGENTMAP-0001  
**Versjon:** 1.0  
**Status:** Aktiv (første versjon)  
**Dato:** 2025-07-22  
**Plassering:** `/00_admin/03_frameworks/04_quality_and_process/agentrolle_metodekart.md`  
**Eier:** Henrik Strand / Norsain Technology Group  

---

## 🎯 Formål

Dokumentet kartlegger hvilke forsknings- og innovasjonsmetoder som knyttes til definerte agentroller i Norsain-plattformen. Det brukes for å sikre metodetilgang, arbeidsdeling og kompetanseforankring i den digitale tvillingstrukturen (DTO).

---

## 🤖 Agentroller og tilknyttede metoder

| Agentrolle                | Tilknyttede metoder og rammeverk                                      | Formål og operativ bruk                                                    |
|---------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Quality Manager Agent** | ISO 9001, TRL, PDCA, FMEA, DSR                                         | Bruker prosess- og risikobasert forbedring for å sikre kvalitet og modenhet |
| **Innovation Strategist Agent** | ISO 56002, Blue Ocean, VPD, BMC, McKinsey 3 Horizons                | Driver systemisk innovasjon og forslag til disruptive skift                  |
| **Foresight Analyst Agent** | Foresight, Scenario Planning, PESTLE, Delphi, Morphological Analysis   | Lager fremtidsscenarier og analyserer teknologitrender                      |
| **Research Architect Agent** | DSR, ETRP, C-K Theory, JTBD, Design Thinking                          | Leder utvikling av teknologiske hypoteser og eksperimentelle artefakter     |
| **Ethics & Impact Agent**  | ALTAI, ToC, OECD TIP, AI Risk Mapping                                 | Vurderer samfunnseffekter, reguleringsrisiko og etikk for ny teknologi      |
| **Business Architect Agent** | BMC, JTBD, Lean Startup, Real Options                                | Matcher teknologi med forretningsverdi, usikkerhet og brukerbehov           |
| **Technology Validator Agent** | TRL, Test-maturity modeller, ISO 50501, Roadmapping                  | Evaluerer teknologimodenhet og utviklingsplaner                             |

---

## 🧭 Bruk

- Brukes som grunnlag for agentbeskrivelser i `/07_agents/`
- Kan kobles videre til `twin.yaml.roles` for å synliggjøre metodekompetanse
- Kan styres gjennom YAML eller supabase-agentregister i DTO-strukturen

---

## 🔄 For videre utvikling

- [ ] Lage YAML-mapping per agentrolle
- [ ] Koble metoder til kompetansematrise
- [ ] Opprette mal for agentrollebeskrivelse med metodefelt
- [ ] Integrere i `agent_behavior.md` og `twin.yaml`

---
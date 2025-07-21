# 🧭 Enterprise Architecture Canvas – Rammeverksoversikt for NextGenio

**Dokument-ID:** NG-FRM-EA-CANVAS-0001  
**Versjon:** 1.0  
**Status:** Utkast – til vurdering  
**Dato:** 2025-07-21  
**Plassering:** `/00_admin/03_frameworks/01_enterprise_architecture/ea_canvas_overview.md`  
**Eier:** Arkitekturansvarlig  

---

## 🎯 Formål

Denne canvasen gir et samlet overblikk over hvordan **NextGenio bruker ulike EA-rammeverk** i samspill. Målet er å skape forståelse for **når** hvert rammeverk er relevant, **hvordan** det brukes i praksis, og **hvorfor** det tilfører verdi i en AI- og dokumentdrevet plattform.

---

## 🧩 EA Canvas – Bruksområder og rammeverk

| Fase / Bruksområde                 | Formål og spørsmål                   | Rammeverk som brukes               | Typisk leveranse                     |
|-----------------------------------|-------------------------------------|------------------------------------|--------------------------------------|
| 🎯 **Strategisk retning**          | Hva prøver vi å oppnå?              | TOGAF (fase A), OKR, BSC, Gartner  | Visjon, Objectives, Outcome Chains   |
| 🗺️ **Forretningskartlegging**      | Hva må vi kunne?                    | Capability Map, BIZBOK             | Kapabilitetskart, verdistrømmer      |
| 🧮 **Styringsmodell**              | Hvordan styrer og måler vi?         | OKR, Balanced Scorecard            | Mål-KPI-matriser, agentmål           |
| 🧱 **Struktur og organisering**    | Hvordan henger alt sammen?          | Operating Model Canvas, BIZBOK     | Canvas, rolle- og informasjonskart   |
| 🖥️ **Systemdesign og komponenter** | Hvordan ser løsningene ut?          | C4 Model, ArchiMate                | Systemdiagrammer, informasjonsflyt   |
| 🔁 **Iterasjon og forbedring**     | Hvordan forbedrer vi kontinuerlig?  | Agile EA, ISO 9001 §10, OKR        | Tilbakemeldingssløyfer, retrospektiv |
| 📊 **Måling og effekt**            | Har vi levert verdi?                | Gartner EA, BSC, Supabase-metrikk  | Outcome-rapport, roadmap-effekt      |

---

## 🔎 Forklaring – Når rammeverkene bør brukes

- **TOGAF**: Startpunkt for strukturert EA-arbeid. Brukes når man trenger helhetlig tilnærming og governance.
- **C4 Model**: Brukes når du skal kommunisere eller designe systemer – spesielt AI-agenters interaksjon og teknisk arkitektur.
- **ArchiMate**: Brukes til mer detaljerte, lagdelte kart – ofte ved sammensatte prosess- og teknologiflyt.
- **Business Capability Map**: Brukes i tidlige faser for å definere hva virksomheten må mestre for å lykkes.
- **Operating Model Canvas**: Knytter strategi til drift – svært nyttig ved MVP og etablering av agentroller.
- **Agile EA**: Brukes løpende for å sikre at arkitekturen utvikles smidig og iterativt, i takt med roadmap.
- **Gartner EA**: Brukes når man vil analysere business outcomes og sørge for at arkitekturen leverer målbart.
- **BIZBOK**: Brukes når man skal knytte strategi til prosjekter og initiativer. Koble målstyring til struktur.
- **OKR**: Brukes kontinuerlig for fremdrift, styring og måling av både agenter og prosesser.
- **Balanced Scorecard**: Brukes som ramme for helhetlig målstyring – særlig i kombinasjon med OKR og ISO-arbeid.

---

## 🧠 Praktisk oppsummering – Hvordan lese denne canvasen

- Gå **radvis**: Identifiser hvilken fase du er i (f.eks. strategisk planlegging).
- Se hvilke **spørsmål** du trenger svar på.
- Velg relevante **rammeverk** for å analysere, modellere eller designe løsningen.
- Bruk eksempelfilene i `01_enterprise_architecture/` som **maler og verktøy**.
- Kombiner flere rammeverk ved behov – f.eks. TOGAF + OKR + Capability Map.

---

## 📄 Dokumentkontroll

| Felt             | Innhold                                  |
|------------------|-------------------------------------------|
| Opprettet av     | Henrik Strand                             |
| Revidert dato    | 2025-07-21                                |
| Versjon          | 1.0                                       |
| Status           | Utkast                                    |
| GitHub-plassering| `/00_admin/03_frameworks/01_enterprise_architecture/` |

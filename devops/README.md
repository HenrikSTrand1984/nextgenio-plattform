# 📘 README – DevOps og Infrastruktur

| Felt                | Innhold                                                   |
|---------------------|-----------------------------------------------------------|
| **Dokument-ID**     | NG-OPS-DEVOPS-README-0001                                 |
| **Versjon**         | 1.0                                                       |
| **Status**          | Aktiv                                                     |
| **Dato**            | 2025-07-19                                                |
| **Eier**            | Henrik Strand – CTO & Kvalitetsleder                      |
| **Plassering GitHub** | `/devops/README.md`                                     |
| **Plassering Dropbox** | `/NextGenio-plattform-04-TechOps-ServiceDelivery/devops/README.md` |

---

## 🎯 Formål

Denne mappen brukes til å dokumentere og versjonsstyre alt arbeid relatert til **DevOps, infrastruktur, CI/CD, sikkerhet og automatisering** i NextGenio-plattformen.

Den dekker også rutiner for miljøoppsett, GitHub Actions, Docker, Jenkins, systemovervåking og pipelines for agent- og systemutvikling.

---

## 🧱 Innhold i mappen

| Fil / Mappe | Beskrivelse |
|-------------|-------------|
| `README.md` | Dette dokumentet – oversikt over formål og struktur |
| `github_actions/` | Workflows for GitHub Actions, CI/CD og testing |
| `jenkins/` | Jenkins-pipelines og konfigurasjonsfiler |
| `docker/` | Dockerfiles og compose-oppsett |
| `env_setup/` | `.env.example`-filer, secrets-policy, miljøspesifikasjoner |
| *(planlagt)* `monitoring/` | Logging, overvåking, varsling og helsesjekk |
| *(planlagt)* `deployment_scripts/` | Bash/PowerShell for automatisk utrulling |
| `versjonslogg.yaml` | Logg over endringer og validerte oppdateringer |

---

## 🔐 Relevante retningslinjer

- [`branch_protection_policy.md`](../admin/governance/branch_protection_policy.md)
- [`supabase_sikkerhet.yaml`](../docs/integrations/supabase/supabase_sikkerhet.yaml)
- [`dokumentpolicy.md`](../admin/governance/dokumentpolicy.md)

---

## 🧾 ISO-standarder i bruk

| Standard | Relevans |
|----------|----------|
| **ISO 27001** | Sikkerhetskontroll, tilgangsstyring og DevSecOps |
| **ISO 9001** | Kvalitetskontroll av DevOps-prosesser |
| **ISO 25010** | Programvarekvalitet og pålitelighet |
| **ISO 20000** | IT-tjenestestyring og operasjonell struktur |

---

## 🧠 Bruksområde

- Bygge og drifte automatiserte DevOps-pipelines for NextGenio-agenter og systemer
- Sikre at kode, infrastruktur og integrasjoner valideres gjennom test og versjonsregler
- Klargjøre miljøoppsett lokalt og i sky (f.eks. GitHub Codespaces)

---

## 📄 Dokumentkontroll

| Felt              | Innhold |
|-------------------|---------|
| **Dokument-ID**   | NG-OPS-DEVOPS-README-0001 |
| **Versjon**       | 1.0 |
| **Status**        | Aktiv |
| **Opprettet**     | 2025-07-19 |
| **Sist revidert** | 2025-07-19 |
| **Godkjent dato** | 2025-07-19 |
| **Dokumenteier**  | Henrik Strand – CTO & Kvalitetsleder |
| **Godkjent av**   | Henrik Strand & AI Assistant |
| **Logg**          | Registrert i `versjonslogg.yaml` og Supabase-autentisert |


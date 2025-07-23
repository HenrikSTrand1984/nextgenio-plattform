# 🏗️ Kapittel 3: Arkitekturoversikt

**Dokument-ID:** NTG-DB-ARCH-PLATFORM-0003  
**Versjon:** 2.0  
**Status:** Ferdigstilt  
**Dato:** 2025-07-23  
**Plassering:** `/01_devops/03_supabase/kapittel_03_arkitekturoversikt.md`  
**Eier:** Henrik Strand / Norsain Technology Group  

---

## 🎯 Formål

Dette kapittelet gir en oversikt over hovedarkitekturen i Norsains dataplattform. Den beskriver hvordan ulike systemkomponenter henger sammen – fra database og API til Git-integrasjon, AI-agentflyt og eksport.

---

## 🧱 Hovedkomponenter

| Lag                       | Komponenter                                  |
|---------------------------|----------------------------------------------|
| 📦 Datagrunnlag           | Supabase SQL-tabeller og lagringsbuckets     |
| 🔐 Tilgangsstyring        | RLS-policyer, metadata, agentroller          |
| 🤖 Agent-API              | OpenAI SDK, HuggingFace, YAML-kontrakter     |
| 🧠 Kontrollag             | DAO-logikk, revisjon, dokumentflow           |
| 🪄 Eksport og revisjon     | ZIP-generator, GitHub-commit, DAO-signatur  |
| 🌐 Frontend               | Netlify frontend for agenter / brukere       |

---

## 🖼️ Systemoversikt (beskrivelse for diagram)

> En illustrasjon kan legges til i `platform_abstraction_layer.drawio` med følgende flyt:

---

## 🔗 Viktige koblinger

- Supabase DB → `documents`, `agents`, `logs`, `buckets`
- GitHub → `git_committer.ts`, `audit_package_builder.ts`
- DAO → `dao_schema.yaml`, `dao_decision_log`
- AI → `agent_register.yaml`, `ai_model_register.yaml`

---

## 🧭 Designprinsipp

- **API-first**: Alle tjenester bygges med offentlig eller intern API-kontrakt
- **Forklarbarhet**: Alle beslutninger er revisjonsklare og agent-identifiserbare
- **Migrerbarhet**: Arkitekturen kan porteres til Azure, Vercel, GCP
- **Komponentisolasjon**: Agenter, buckets og tabeller er løst koblet

---

## 📎 Neste steg

Kapittel 4 forklarer databasen og hovedtabellene i Supabase.

---

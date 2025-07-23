# 🗃️ Kapittel 4: Datamodell og hovedtabeller

**Dokument-ID:** NTG-DB-ARCH-PLATFORM-0004  
**Versjon:** 2.0  
**Status:** Ferdigstilt  
**Dato:** 2025-07-23  
**Plassering:** `/01_devops/03_supabase/kapittel_04_datamodell_hovedtabeller.md`  
**Eier:** Henrik Strand / Norsain Technology Group  

---

## 🎯 Formål

Dette kapittelet beskriver hovedtabellene og datamodellen som benyttes i Supabase-databasen til Norsain. Alle tabeller er designet i henhold til:
- ISO 9001:2015 – dokumentstyring og revisjon
- ISO/IEC 27001 – tilgang, integritet og sporbarhet
- ISO/IEC 42001 – agentkontroll og AI-sporing

---

## 📐 Hovedtabeller

| Tabellnavn         | Formål                                           |
|--------------------|--------------------------------------------------|
| `documents`        | Alle prosedyrer, policyer, skjema og maler       |
| `document_versions`| Historikk og revisjonskontroll                   |
| `agents`           | Register over aktive AI-/QMS-agenter             |
| `agent_logs`       | Hendelser, beslutninger og forklaringsnivå       |
| `dao_proposals`    | DAO-godkjenningssaker                            |
| `dao_votes`        | Stemmer og kvoteverdi i DAO-systemet             |
| `git_commit_log`   | Sporing av push og signatur til GitHub           |
| `audit_exports`    | Metadata for eksportpakker (ZIP/PDF/CSV)         |
| `buckets`          | Oversikt over filsystem og bucketinnhold         |

---

## 🧱 Supplerende støttetabeller

| Tabellnavn         | Innhold                                         |
|--------------------|--------------------------------------------------|
| `user_access`      | Brukere, agenter og RLS-policy                   |
| `iso_references`   | ISO-koder knyttet til dokumenter og tabeller    |
| `metadata_registry`| Katalog over datatyper, versjon og kilde        |
| `document_tags`    | Kategorisering og søkbare nøkkelord             |

---

## 🧩 Eksempel: Supabase-tabell `documents`

```sql
CREATE TABLE documents (
  id UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  doc_id TEXT NOT NULL,
  title TEXT,
  doc_type TEXT CHECK (doc_type IN ('policy', 'procedure', 'form')),
  iso_ref TEXT,
  current_version TEXT,
  created_at TIMESTAMP DEFAULT now(),
  updated_at TIMESTAMP DEFAULT now(),
  is_active BOOLEAN DEFAULT true
);
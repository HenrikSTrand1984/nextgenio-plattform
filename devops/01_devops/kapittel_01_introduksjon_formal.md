# 📘 Kapittel 1: Introduksjon og formål

**Dokument-ID:** NTG-DB-ARCH-PLATFORM-0001  
**Versjon:** 2.0  
**Status:** Ferdigstilt  
**Dato:** 2025-07-23  
**Plassering:** `/01_devops/03_supabase/kapittel_01_introduksjon_formal.md`  
**Eier:** Henrik Strand / Norsain Technology Group  

---

## 🎯 Formål

Dette dokumentet beskriver hele dataplattformarkitekturen til Norsain Technology Group slik den er implementert med Supabase, GitHub, Netlify og AI-integrasjoner.  

Det fungerer både som:
- ✅ Teknisk spesifikasjon for utvikling og DevOps
- ✅ Dokumentasjonsgrunnlag for ISO 9001, 27001, 42001 og 15489
- ✅ Vedlegg til patentsøknad knyttet til "Living Operating System for the Enterprise"
- ✅ Grunnlag for eksport og publisering til partner, revisor og DAO

---

## 🧱 Omfang

Plattformen dekker følgende hovedelementer:

| Område                       | Innhold                                                                 |
|-----------------------------|-------------------------------------------------------------------------|
| Supabase database           | SQL-modell, policyer, dokumenter, loggføring                            |
| Agent-API og SDK-integrasjon| OpenAI, HuggingFace, GitHub                                             |
| DAO-beslutninger            | Desentralisert godkjenning og signaturprosess                           |
| Fil- og metadatahåndtering | Buckets, filversjoner og ISO-koblinger                                 |
| Eksport og revisjonspakker | Full ZIP inkl. metadata, signatur og sporbarhet                         |

---

## 📎 Relaterte dokumenter

- `platform_data_architecture_norsain.md` (hovedfil)
- `data_export_policy.yaml`
- `agent_register.yaml`
- `audit_package_builder.ts`
- `supabase_tablemap.sql`

---
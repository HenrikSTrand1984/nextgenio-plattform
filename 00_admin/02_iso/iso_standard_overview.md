---
title: ISO Standard Overview
version: 1.0
status: Draft
created: 2025-07-23
author: Henrik Strand / ISO Documentation Project
email: info@norsain.com
doc-id: ISO-OVERVIEW-001
path: /02_iso/00_overview/iso_standard_overview.md
---

# 📘 ISO Standard Overview

## 🧾 1. About ISO

The **International Organization for Standardization (ISO)** is an independent, non-governmental international organization founded in 1947, headquartered in Geneva, Switzerland. ISO brings together national standards bodies from over 170 countries to develop and publish internationally agreed standards.

### 🔍 What ISO does:
- Develops **International Standards** to promote quality, safety, sustainability and efficiency.
- Facilitates **global interoperability** across products, systems and services.
- Supports **innovation, governance and compliance** across sectors and disciplines.

## 🔢 2. ISO’s Classification System – ICS

ISO uses the **International Classification for Standards (ICS)** to organize standards hierarchically:

| Level        | Code format     | Description                                      |
|--------------|------------------|--------------------------------------------------|
| Field        | `NN`             | High-level sector (e.g., 35 = IT, 27 = Energy)   |
| Group        | `NN.NNN`         | Sub-sector / thematic category                   |
| Subgroup     | `NN.NNN.NN`      | Specific subject within the group                |
| Optional 4th | `NN.NNN.NN-XX`   | Internal customization (used by orgs)            |

ICS is maintained by ISO Central Secretariat and ensures traceability and grouping of all published ISO standards.

## 🧩 3. ISO Standard Types

| Type                  | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| **IS (International Standard)** | Formal, consensus-based publication                                |
| **TS (Technical Specification)** | Preliminary documents not yet matured into IS                     |
| **TR (Technical Report)**        | Informative documents, not requirements                           |
| **PAS (Publicly Available Specification)** | Fast-tracked specs with shorter development cycles        |
| **Guide**                        | Non-binding best-practice support documents                      |

---

## 📚 4. ISO Fields and Sectors (ICS Fields)

ISO organizes all standards into approximately 40 top-level ICS fields:

| ICS | Sector                                |
|-----|----------------------------------------|
| 01  | Generalities, terminology, standards writing |
| 03  | Services, company organization, management and quality |
| 07  | Mathematics, natural sciences          |
| 11  | Health care technology                 |
| 13  | Environmental protection, safety       |
| 17  | Metrology and measurement              |
| 19  | Testing and calibration                |
| 21–49 | Engineering sectors (mechanical, fluid, electrical, etc.) |
| 27  | Energy and heat transfer engineering   |
| 29–33 | Electrical engineering, electronics, ICT |
| 35  | Information technology                 |
| 37  | Image processing, terminology          |
| 43–49 | Transport sectors (road, rail, marine, aerospace) |
| 55  | Packaging and distribution             |
| 65–75 | Food, agriculture, petroleum          |
| 91  | Construction and civil engineering     |
| 93  | Infrastructure (roads, water, pipelines) |

> A complete ICS list is available at: [ISO ICS Catalog](https://www.iso.org/ics.html)

---

## 📐 5. Documentation Methodology

To ensure consistency, traceability, and integration readiness, ISO standards documentation in this project follows the principles of:

### 🎓 ISO-Based Frameworks:
- **ISO/IEC Directives Part 1** – rules for standard development
- **ISO 10013** – guidelines for quality system documentation
- **ISO 9001:2015 Clause 7.5** – documented information
- **ICS hierarchy** – for structured categorization

### 📋 Core Method Rules:
1. **Full ICS hierarchy** is used to index all standards.
2. **Tabular format** with three columns: ICS code, ISO standard name, description.
3. **Each sector** gets its own dedicated table.
4. **Version, status, year** of the standard is tracked if possible.
5. **Sourcing** is traceable back to ISO.org or national standardization bodies.

---

## ✅ Next Steps

- Proceed to: `03_register/iso_standards_by_sector.md`  
- Goal: Full ISO standard register categorized by ICS fields.
- Output: Markdown + YAML format for integration with Supabase/Draw.io/QMS.


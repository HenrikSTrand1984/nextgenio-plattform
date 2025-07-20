# 📁 Audits

**Document ID:** NG-QLT-README-0102  
**Version:** 1.0  
**Status:** Active  
**Date:** 2025-07-20  
**Location (GitHub):** `/01_admin/04_quality_system/02_audits/`  
**Location (Dropbox/SharePoint):** `NextGenio-Platform/01_Admin/04_QualitySystem/02_Audits/`  

---

## 🎯 Purpose

This folder contains all content related to **audits**, including audit programs, plans, checklists, reports, and follow-up actions.

Audits are conducted to ensure that the quality management system:
- Conforms to ISO 9001:2015 requirements and internal procedures  
- Is effectively implemented and maintained  
- Supports continual improvement and compliance in the NextGenio platform

---

## 📘 Scope

Covers the full internal audit lifecycle as defined in ISO 9001:2015 clause 9.2:

- **Audit planning and scheduling**  
- **Execution (checklists, interviews, evidence)**  
- **Reporting of findings**  
- **Corrective and improvement follow-up**

Also includes special audits (e.g. triggered by nonconformities, management reviews or agent malfunctions).

---

## 📂 Folder Content

| Filename | Description | Type |
|----------|-------------|------|
| `audit_plan_2025.md` | Annual audit plan (example) | Markdown |
| `audit_checklist_template.md` | Standardized checklist template | Markdown |
| `audit_report_template.md` | Template for writing audit findings | Markdown |
| `audit_log.yaml` | Central audit log for tracking audits, findings, and status | YAML |

---

## 🛠️ Usage Instructions

1. Maintain the audit plan file (`audit_plan_202X.md`) with updated scope and dates.
2. Use the checklist template for consistent audit execution.
3. Document all findings using the report template.
4. Enter each audit and its status in `audit_log.yaml`.
5. Link relevant findings to `/03_nonconformities/` or `/04_improvement/` as needed.

Audit activities must be conducted by qualified personnel not directly responsible for the audited area, per ISO 9001:2015.

---

## 🔗 Related Folders

- `/01_admin/04_quality_system/03_nonconformities/` – for deviations found in audits  
- `/01_admin/04_quality_system/04_improvement/` – for improvement actions from audits  
- `/01_admin/07_decision_log/` – for documented outcomes or escalations  

---

## 📄 Document Control

| Field         | Value               |
|---------------|---------------------|
| Created by    | Henrik Strand        |
| Maintained by | Quality Manager      |
| Reviewed by   | [Name]               |
| Approved by   | Henrik Strand, [Name] |
| Last updated  | 2025-07-20           |
| Version log   | See `audit_log.yaml` |


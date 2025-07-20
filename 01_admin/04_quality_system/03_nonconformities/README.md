# 📁 Nonconformities and Deviations

**Document ID:** NG-QLT-README-0103  
**Version:** 1.0  
**Status:** Active  
**Date:** 2025-07-20  
**Location (GitHub):** `/01_admin/04_quality_system/03_nonconformities/`  
**Location (Dropbox/SharePoint):** `NextGenio-Platform/01_Admin/04_QualitySystem/03_Nonconformities/`  

---

## 🎯 Purpose

This folder documents all registered **nonconformities, deviations, and compliance gaps** identified in the NextGenio platform’s operations, products, or processes. It supports ISO 9001:2015 clause 10.2 on **nonconformity and corrective action**.

The purpose is to ensure systematic handling of undesired events, including root cause analysis, containment, corrective measures, and documentation for future prevention.

---

## 📘 Scope

Covers all types of nonconformities and related actions, including:

- Quality-related process deviations  
- Compliance gaps (e.g. ISO, internal policies)  
- Agent behavior or logic failures  
- Technical or procedural errors  
- User-reported inconsistencies

This applies across the full lifecycle and all roles in the NextGenio organization.

---

## 📂 Folder Content

| Filename | Description | Type |
|----------|-------------|------|
| `nonconformity_log_template.md` | Template for documenting NCs and actions | Markdown |
| `QLT-NC-0001_missing_doc_control.md` | Example of a nonconformity entry | Markdown |
| `nonconformity_register.yaml` | Overview log of all NCs and their status | YAML |

---

## 🛠️ Usage Instructions

1. Use `nonconformity_log_template.md` to register new deviations or incidents.
2. Save as a new Markdown file using the format `QLT-NC-XXXX_description.md`.
3. Log all new entries and updates in `nonconformity_register.yaml`.
4. Conduct root cause analysis, define actions, assign responsibility, and follow-up.
5. Where appropriate, link to `/04_improvement/` or `/09_change_management/`.

Each NC entry must be closed or escalated by a Quality Manager or designated agent.

---

## 🔗 Related Folders

- `/01_admin/04_quality_system/01_procedures/` – handling procedures  
- `/01_admin/04_quality_system/04_improvement/` – related improvement actions  
- `/01_admin/09_change_management/` – systemic changes from NCs  
- `/01_admin/07_decision_log/` – decisions tied to deviation handling  

---

## 📄 Document Control

| Field         | Value               |
|---------------|---------------------|
| Created by    | Henrik Strand        |
| Maintained by | Quality Manager      |
| Reviewed by   | [Name]               |
| Approved by   | Henrik Strand, [Name] |
| Last updated  | 2025-07-20           |
| Version log   | See `nonconformity_register.yaml` |

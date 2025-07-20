# 👥 Role Register – NextGenio Platform

| Field            | Content                                                   |
|------------------|------------------------------------------------------------|
| **Document ID**  | NG-GOV-ROLES-0001                                          |
| **Version**      | 1.0                                                        |
| **Status**       | Active                                                     |
| **Date**         | 2025-07-20                                                 |
| **Location**     | `/00_admin/01_governance/04_role_descriptions/role_register_nextgenio.md` |
| **Owner**        | Henrik Strand / Quality Manager                            |

---

## 🎯 Purpose

This document provides a complete register of key roles in the NextGenio platform.  
Each role is documented in a dedicated `.md` file, linked to governance, policies, ISO standards, and the multi-agent system.

---

## 🧱 Categories and Role Structure

### 🧭 Governance and Compliance

Roles that ensure the platform operates in alignment with ISO standards, legal frameworks, and internal governance structures. These roles handle responsibility, documentation integrity, approvals, audits, and quality.

| File name                  | Role title (Norwegian)    | Description |
|----------------------------|---------------------------|-------------|
| `quality_manager.md`       | Kvalitetsleder            | Manages the quality system and ISO 9001 compliance |
| `compliance_manager.md`    | Complianceansvarlig       | Ensures legal, ISO 27001, and GDPR compliance |
| `process_owner.md`         | Prosesseier               | Owns and oversees business processes |
| `audit_lead.md`            | Revisjonsleder            | Leads internal audits and compliance reviews |
| `risk_manager.md`          | Risikoansvarlig           | Responsible for risk assessments and mitigations |

---

### 👨‍💻 Technology and Development

Roles related to technical operations, system architecture, integrations, and DevOps processes. These functions are foundational for agent deployment, CI/CD, and platform stability.

| File name                  | Role title (Norwegian)    | Description |
|----------------------------|---------------------------|-------------|
| `system_owner.md`          | Systemansvarlig           | Owns platform architecture and technical documentation |
| `devops_lead.md`           | DevOps-leder              | Responsible for CI/CD, deployment, and environment management |
| `integration_manager.md`   | Integrasjonsansvarlig     | Manages third-party systems and API integrations |
| `data_steward.md`          | Datakvalitetsansvarlig    | Oversees data definitions, access, and quality |

---

### 📚 Knowledge and Documentation

Roles dedicated to structuring, curating, and maintaining all documentation, templates, learning modules, and internal knowledge bases.

| File name                  | Role title (Norwegian)    | Description |
|----------------------------|---------------------------|-------------|
| `documentation_manager.md` | Dokumentasjonsansvarlig   | Manages document structure, versions, and metadata |
| `learning_manager.md`      | Læringsansvarlig          | Responsible for onboarding, guides, and documentation for training |
| `method_curator.md`        | Metodekurator             | Maintains the integrity and catalog of methods and frameworks |
| `standard_manager.md`      | Standardansvarlig         | Tracks ISO standards and related internal guidelines |

---

### 🤖 Agents and AI Operations

These roles support the design, coordination, evaluation, and improvement of agents in the multi-agent architecture of NextGenio. Roles ensure agent explainability, functionality, and structured documentation.

| File name                  | Role title (Norwegian)    | Description |
|----------------------------|---------------------------|-------------|
| `agent_coordinator.md`     | Agentkoordinator          | Coordinates all agents and their configurations |
| `ai_training_lead.md`      | Læringsleder for AI       | Oversees dataset management, prompt tuning and model evaluation |
| `agent_reviewer.md`        | Agentrevisor              | Responsible for performance audits and quality control of agents |
| `function_designer.md`     | Funksjonsdesigner         | Designs YAML/API functions for agents and connects them to tools |

---

### 📊 Platform Management and Execution

Core ownership and delivery roles responsible for leading implementation, project coordination, and platform-level decisions.

| File name                  | Role title (Norwegian)    | Description |
|----------------------------|---------------------------|-------------|
| `project_manager.md`       | Prosjektleder             | Manages project progress, tasks, and milestone delivery |
| `platform_owner.md`        | Plattformeier             | Holds final responsibility for the NextGenio platform’s design and delivery |

---

## 🧠 Usage

- Every role listed must be documented in `/00_admin/01_governance/04_role_descriptions/`.
- Each role file must follow the standard markdown template: `role_description.md`.
- Changes must be approved and recorded in `versjonslogg.yaml`.

---

## 📎 Related Documents

- `dokumentpolicy.md`
- `mappepolicy.md`
- `godkjenning_policy.md`
- `role_description.md` (template)
- `versjonslogg.yaml`

---

## 📄 Document Control

| Field           | Content                |
|-----------------|------------------------|
| Created by      | Henrik Strand          |
| Revised date    | 2025-07-20             |
| Approved by     | [To be filled]         |
| Status          | Active                 |
| Version         | 1.0                    |

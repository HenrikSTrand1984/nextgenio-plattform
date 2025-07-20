# 🏗️ Architecture Register – NextGenio Platform

| Field            | Content                                                        |
|------------------|-----------------------------------------------------------------|
| **Document ID**  | NG-GOV-ARCH-REGISTER-0001                                       |
| **Version**      | 1.0                                                             |
| **Status**       | Active                                                          |
| **Date**         | 2025-07-20                                                      |
| **Location**     | `/00_admin/05_templates/10_architecture/architecture_register.md` |
| **Owner**        | Henrik Strand / Quality Manager                                 |

---

## 🎯 Purpose

This register tracks all architectural diagrams, models, and visual frameworks used to describe the NextGenio platform.  
It includes TOGAF-based enterprise models, C4 system architecture, deployment visuals, and data flows.

---

## 🧱 Enterprise Architecture (TOGAF)

| Filename                      | Title                         | Format    | Description |
|-------------------------------|-------------------------------|-----------|-------------|
| `enterprise_capabilities.drawio` | Enterprise Capabilities Map | `.drawio` | Visual overview of business functions and capabilities |
| `architecture_principles.md`  | Architecture Principles       | `.md`     | Key guiding principles for design decisions |
| `togaf_layers_overview.svg`  | TOGAF Layered Architecture     | `.svg`    | Overview of business, app, data, tech layers |

---

## 📦 System Architecture (C4)

| Filename                      | Title                         | Format    | Description |
|-------------------------------|-------------------------------|-----------|-------------|
| `system_context.drawio`       | System Context Diagram        | `.drawio` | High-level external systems view |
| `c4_container_view.drawio`    | Container Diagram             | `.drawio` | Main services and applications |
| `c4_component_view.drawio`    | Component Diagram             | `.drawio` | Code- and module-level components |

---

## 🔁 Process & Sequence Diagrams

| Filename                        | Title                         | Format    | Description |
|----------------------------------|-------------------------------|-----------|-------------|
| `agent_sequence_flow.drawio`    | Agent Sequence Flow           | `.drawio` | Message-passing between AI agents |
| `login_flow_sequence.md`        | Login Flow Sequence           | `.md`     | Authentication + RLS logic |
| `deployment_sequence.mermaid`   | Deployment Steps              | `.mermaid`| CI/CD execution process |

---

## 🧮 Data & Integration Architecture

| Filename                         | Title                         | Format    | Description |
|----------------------------------|-------------------------------|-----------|-------------|
| `supabase_structure.svg`         | Supabase Entity Diagram       | `.svg`    | Tables, views, and access roles |
| `api_integration_map.drawio`     | External API Map              | `.drawio` | Links to OpenAI, Dropbox, GitHub |
| `data_flow_pipeline.drawio`      | Data Pipeline Diagram         | `.drawio` | Flow from input to LLM + logging |

---

## 📎 Related Documents

- `data_models_register.md`
- `function_templates/`
- `checklist_register.md`
- `architecture_principles.md`

---

## 📄 Document Control

| Field           | Content                |
|-----------------|------------------------|
| Created by      | Henrik Strand          |
| Revised date    | 2025-07-20             |
| Approved by     | [To be filled]         |
| Status          | Active                 |
| Version         | 1.0                    |

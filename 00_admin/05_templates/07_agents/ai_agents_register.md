# 🤖 AI Agents Register – NextGenio Platform

| Field            | Content                                                     |
|------------------|--------------------------------------------------------------|
| **Document ID**  | NG-AGENT-REGISTER-0001                                       |
| **Version**      | 1.0                                                          |
| **Status**       | Active                                                       |
| **Date**         | 2025-07-20                                                   |
| **Location**     | `/00_admin/05_templates/07_agents/ai_agents_register.md`             |
| **Owner**        | Henrik Strand / Quality Manager                              |

---

## 🎯 Purpose

This register lists all AI agents developed and deployed as part of the NextGenio multi-agent system.  
Each agent is defined by a clear purpose, configuration file (YAML or JSON), role responsibility, and documentation linkage.

---

## 🧠 Registered Agents

| Agent ID          | Name                | Purpose / Description | Config File |
|-------------------|---------------------|------------------------|-------------|
| `agent-001`       | Quality Manager     | Ensures ISO compliance, structure, and governance alignment | `quality_manager.yaml` |
| `agent-002`       | Research Assistant  | Performs market, trend, and academic research | `research_assistant.yaml` |
| `agent-003`       | Project Manager     | Coordinates milestones, updates and OKRs | `project_manager.yaml` |
| `agent-004`       | Documentation Agent | Maintains README.md, templates and doc policy | `documentation_agent.yaml` |
| `agent-005`       | System Monitor      | Observes uptime, logs, and alerts in Supabase/OpenAI stack | `system_monitor.yaml` |
| `agent-006`       | Integration Agent   | Manages API bindings and external service connections | `integration_agent.yaml` |

---

## 🧾 Agent Metadata

Each agent is defined by:
- A unique ID and name
- A YAML configuration file for tools, instructions, memory and functions
- Role description file (e.g. `quality_manager.md`)
- Deployment log and versioning

Agents are categorized by:
- 🎯 Function (compliance, research, ops, etc.)
- ⚙️ Integration needs (Supabase, OpenAI, APIs)
- 🔁 Update cycle (static, dynamic, retrained)

---

## 📎 Related Documents

- `role_register_nextgenio.md`
- `function_template.yaml`
- `checklist_register.md`
- `architecture_register.md`

---

## 📄 Document Control

| Field           | Content                |
|-----------------|------------------------|
| Created by      | Henrik Strand          |
| Revised date    | 2025-07-20             |
| Approved by     | [To be filled]         |
| Status          | Active                 |
| Version         | 1.0                    |

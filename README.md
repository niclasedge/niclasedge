### Hi, I'm Niclas 👋

System engineer for process automation at an IT service provider (Cologne, Germany). I automated processes before the AI wave; AI is the multiplier that makes more of them standardizable.

Most processes run more reliably once they are standardized: a clean intake channel, a clear definition, implementation to a standard. Language models and agents handle the rest, and they are reliable only with clear guidelines, schemas and gates. At work, about half of our standard tickets now run fully automated, the rest partly automated.

This profile shows the parts I build in my own time, in three areas. Blog, notes and the full tool list: [niclasedge.github.io](https://niclasedge.github.io).

#### AI governance: keep data and secrets out of the model

| Repo | What it does |
|---|---|
| [tollgate](https://github.com/niclasedge/tollgate) | Auditable gateway in front of the Claude API: redaction, compression, metering (Go) |
| [rust-redactor](https://github.com/niclasedge/rust-redactor) | Redacts secrets and PII in agent tool calls, as a hook for Claude Code, Codex and OpenCode (Rust) |
| [claude-code-dsgvo-hooks](https://github.com/niclasedge/claude-code-dsgvo-hooks) | Blocks personal data (GDPR/DSGVO), secrets and risky tool calls before they reach the model (Python) |
| [sopsy](https://github.com/niclasedge/sopsy) | SOPS + age secrets in one binary for macOS, Linux and Windows (Go) |

#### Agents in production: specs, schedules, evidence

| Repo | What it does |
|---|---|
| [agent-planner](https://github.com/niclasedge/agent-planner) | Scheduled Claude agents on Linux: systemd timers, Claude Agent SDK, per-run logs, web UI (TypeScript) |
| [ops-lab](https://github.com/niclasedge/ops-lab) | Spec-driven workflow for AI coding agents: OpenSpec changes, machine-checked gates, measured token cost |
| [live-plan](https://github.com/niclasedge/live-plan) | Agent skill: a live session document with questions, steps and evidence for the human in the loop |
| [llm-evals](https://github.com/niclasedge/llm-evals) | Compare LLMs on the same tasks with LLM-judge scoring and promptfoo configs (Python) |

#### Processes, architecture and platform

| Repo | What it does |
|---|---|
| [process-atlas](https://github.com/niclasedge/process-atlas) | Browse BPMN 2.0 diagrams with drill-down into called sub-processes |
| [archgraph](https://github.com/niclasedge/archgraph) | Multi-perspective architecture diagrams from declarative YAML |
| [git-planner-go](https://github.com/niclasedge/git-planner-go) | GitHub issues dashboard with epic maps, evidence and MCP ingest (Go) |
| [iac-stack-template](https://github.com/niclasedge/iac-stack-template) | Template for a small multi-host platform: Ansible deploys, monitoring with GitHub-issue alerts, SOPS secrets |

**Stack:** Python · Go · TypeScript · Rust · PowerShell · Ansible · Docker · Azure / Microsoft 365 · Power Automate · Hono + htmx · Claude Code / Agent SDK

**Languages:** German (native), English

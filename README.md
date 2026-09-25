# BA Course: Using Claude Code Inside Claude Code

> A hands-on course for Senior Business Analysts — taught by Claude Code, using Claude Code, to do real BA work with Claude Code.

---

## What This Is

This is a project-based BA training course. You play the role of a Senior BA at **NovaTech Solutions**, a FinTech company building an AI-powered compliance triage feature called **SmartAlert**. You complete a full BA engagement — from discovery to executive readout — using Claude Code as your primary tool throughout.

The meta design is intentional: **you learn Claude Code by using it to do your actual job.**

---

## Prerequisites

- [Claude Code](https://claude.ai/download) installed
- Anthropic account with Claude Code access
- Basic familiarity with business analysis (this is a Senior BA course, not BA 101)
- Git (for cloning the reference codebase in Module 3)

---

## Quick Start

```bash
# 1. Clone the course repo
git clone https://github.com/YOUR_USERNAME/nextgenit-ba-claude-code
cd nextgenit-ba-claude-code

# 2. Open Claude Code
claude

# 3. Start the course
> start module 0
```

Claude Code will read `CLAUDE.md` automatically and act as your course instructor. Tell it which lesson you're on. It will guide you from there.

---

## Course Structure

| Module | Topic | Key Claude Code Skill |
|---|---|---|
| **0 — Foundations** | Claude Code setup, CLAUDE.md, custom commands | CLAUDE.md authoring, command creation |
| **1 — Discovery** | Interview synthesis, gap analysis, discovery backlog | Multi-document synthesis |
| **2 — Problem Framing** | Problem statement, MoSCoW scope, alignment memo | Iterative document drafting |
| **3 — Codebase Intelligence** | Reading code as a BA, Mermaid diagrams, gap analysis | Code exploration, diagram generation |
| **4 — Requirements** | Functional/NFR requirements, business rules, risk register | Template-driven generation |
| **5 — Feature Design** | User stories, Gherkin, data contracts | Gherkin generation, schema design |
| **6 — UX Documentation** | HTML wireframes, interactive prototypes, UX critique | Wireframe and prototype generation |
| **7 — Delivery Planning** | Dependency mapping, phased roadmap, sprint plan | Dependency and timeline modeling |
| **8 — Validation** | UAT test cases, traceability matrix, executive readout | Multi-artifact synthesis |

**Total:** 26 lessons | 25 deliverable artifacts | 1 complete BA engagement

---

## The Project Scenario

**Company:** NovaTech Solutions — Enterprise FinTech, trade compliance
**Feature:** SmartAlert — AI-powered compliance alert triage for TradeWatcher
**Your role:** Senior BA, sole BA on the project
**Deadline:** March 15 (requirements), Q2 board demo

**The challenge:** The CTO wants "AI automation in 90 days." The CCO says "humans must sign off — always." The CISO says "no trade data leaves the perimeter." The Engineering Lead says "give me a data model before you write a single story." Your job is to navigate all of this.

---

## Pre-Built Custom Commands

These slash commands are available from day one:

| Command | When to use |
|---|---|
| `/ba-synthesize` | Turn raw interview notes into a structured matrix |
| `/ba-requirements` | Generate FRs and NFRs from discovery context |
| `/ba-stories` | Create user stories with Gherkin acceptance criteria |
| `/ba-diagram` | Generate Mermaid architecture/flow diagrams |
| `/ba-risks` | Build a risk register from project materials |
| `/ba-readout` | Draft an executive summary from all artifacts |

---

## Course Philosophy

This course treats you as a **senior peer**, not a student. Lessons are direct. Expectations are professional. Claude Code will critique weak output and tell you why. Your deliverables should be indistinguishable from real BA artifacts produced in an actual engagement.

**The core lesson:** Claude Code is a thinking partner, not a thinking replacement. You direct it. You review its output. You apply professional judgment. It drafts, synthesizes, and formats. You decide.

---

## File Structure

```
nextgenit-ba-claude-code/
├── CLAUDE.md                    ← Course instructor rules (auto-loaded by Claude Code)
├── .claude/commands/            ← 6 pre-built BA slash commands
├── course-context/              ← Company background, stakeholder personas
├── discovery-results/           ← Mock interviews, Slack fragments, Jira backlog
├── modules/                     ← 26 lessons across 9 modules
│   ├── module-00-foundations/
│   ├── module-01-discovery/
│   ├── module-02-problem-framing/
│   ├── module-03-codebase-intelligence/
│   ├── module-04-requirements/
│   ├── module-05-feature-design/
│   ├── module-06-ux-docs/
│   ├── module-07-delivery/
│   └── module-08-validation/
├── artifacts/                   ← Your deliverables go here (empty at start)
└── course-repo/                 ← Cloned reference codebase (see Module 3)
```

---

## License

CC BY-NC-ND 4.0 — See `LICENSE`

---

## Credits

Course designed as a parallel to the [NextGen IT BA Antigravity course](https://github.com/ioannWILL/nextgenit-ba-antigravity). Same BA curriculum, same real-world scenario approach — adapted for Claude Code instead of Antigravity IDE.

# OctoAcme — RACI / Ownership Matrix Template

## Purpose
Provide a lightweight, reusable template for mapping roles to project activities. Use this at the start of every project (during Initiation or Planning) to prevent ownership gaps, reduce handoff friction, and give all team members a clear picture of who does what.

## How to use this template
1. Copy the blank matrix below into your project's `docs/` folder (e.g., `docs/raci-<project-name>.md`).
2. Fill in the activities relevant to your project, removing rows that do not apply.
3. Assign one RACI code per cell using the legend below.
4. Review with the team at kickoff and update whenever scope or personnel changes.

## RACI Legend

| Code | Meaning |
|---|---|
| **R** — Responsible | Does the work. At least one role must be R for each activity. |
| **A** — Accountable | Owns the outcome; the final decision-maker. Exactly one role per row. |
| **C** — Consulted | Provides input before or during the activity (two-way communication). |
| **I** — Informed | Kept up to date on progress or decisions (one-way communication). |
| *(blank)* | Not involved in this activity. |

---

## Blank RACI Matrix

> **Instructions:** Replace `[Project Name]` and the example activities below with your project's actual activities. Add or remove columns for roles not present on your team.

**Project:** [Project Name]
**Date:** [YYYY-MM-DD]
**Owner (ProjM):** [Name]

| Activity | ProjM | PdM | Developer | UX/UI Designer | Data Analyst | Scrum Master | Stakeholder | QA/Testing |
|---|---|---|---|---|---|---|---|---|
| Define problem statement & success metrics | C | A/R | I | C | C | I | C | I |
| Create Project One-pager / Charter | A/R | C | I | I | I | I | I | I |
| Stakeholder alignment & approval | R | C | I | I | I | I | A | I |
| Draft RACI Matrix | A/R | C | I | I | I | C | I | I |
| Backlog creation & prioritization | C | A/R | C | C | C | C | I | C |
| UX research & wireframe review | I | A | C | R | I | I | C | I |
| Sprint planning | C | C | C | C | I | A/R | I | C |
| Feature development | I | C | A/R | C | I | I | I | C |
| Analytics instrumentation | I | C | R | I | A | I | I | I |
| QA / acceptance testing | C | C | C | I | I | I | I | A/R |
| Sprint review / demo | C | C | R | R | R | A/R | I | R |
| Release sign-off | A | C | C | I | I | I | R | C |
| Post-release metrics review | I | A | I | I | R | I | C | I |
| Retrospective facilitation | C | I | C | C | I | A/R | I | C |
| Risk register updates | A/R | C | C | I | C | C | I | I |

---

## Filled-in Example

The example below shows a sample RACI for a fictional "User Dashboard Redesign" project.

**Project:** User Dashboard Redesign
**Date:** 2026-03-01
**Owner (ProjM):** Alex Kim

| Activity | ProjM (Alex) | PdM (Priya) | Developer (Dev Team) | UX/UI Designer (Sam) | Data Analyst (Jordan) | Scrum Master (Taylor) | Stakeholder (VP Product) | QA/Testing (QA Team) |
|---|---|---|---|---|---|---|---|---|
| Define success metrics | C | A/R | I | C | C | I | C | I |
| Project Charter approved | A/R | C | I | I | I | I | A | I |
| Stakeholder alignment | R | C | I | I | I | I | A | I |
| Wireframe review | I | A | C | R | I | I | C | I |
| Sprint planning | C | C | C | C | I | A/R | I | C |
| Dashboard feature build | I | C | A/R | C | I | I | I | C |
| Analytics instrumentation | I | C | R | I | A | I | I | I |
| UAT / acceptance testing | C | C | C | I | I | I | I | A/R |
| Release sign-off | A | C | C | I | I | I | R | C |
| Post-release metrics review | I | A | I | I | R | I | C | I |
| Retrospective | C | I | C | C | I | A/R | I | C |

---

## Tips & Best Practices

- **One Accountable per row.** If you find multiple A's on a row, clarify ownership before the project starts.
- **Too many C's slows decisions.** Limit Consulted to those whose input is genuinely required.
- **Keep Informed lists lean.** Over-informing leads to notification fatigue; use status reports or dashboards instead.
- **Revisit at each phase gate.** The RACI should evolve as the project moves from Initiation → Planning → Execution → Release.
- **Link from your Project Charter.** Add a reference to this RACI in the Project One-pager so it is easy to find.

---

## Related Documents
- [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) — canonical role definitions and the Role Interaction Map
- [`octoacme-project-initiation.md`](octoacme-project-initiation.md) — when to create the RACI (Initiation Checklist)
- [`octoacme-project-planning.md`](octoacme-project-planning.md) — confirm RACI during Planning Checklist
- [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) — refer to RACI when clarifying ownership during execution

# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (ProjM) and Product Manager (PdM).
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
For full role definitions, responsibilities, and interaction maps, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

| Role | Abbreviation | Primary Responsibility |
|---|---|---|
| Project Manager | **ProjM** | Coordinates delivery, schedules, risk, and communications |
| Product Manager | **PdM** | Defines outcomes, prioritizes backlog, and measures success |
| Developer | — | Implements features; collaborates on design and testability |
| UX/UI Designer | — | Ensures usability and visual quality of delivered features |
| Data Analyst | — | Instruments and measures success metrics; provides insights |
| Scrum Master / Agile Coach | — | Facilitates ceremonies, removes impediments, coaches the team |
| Stakeholder | — | Provides input, approvals, and represents business/customer needs |
| QA/Testing | — | Validates quality and acceptance criteria |

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- RACI / Ownership Matrix (see [`octoacme-raci-matrix-template.md`](octoacme-raci-matrix-template.md))
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between ProjM + PdM
- Twice-weekly standups for delivery team (or as agreed), facilitated by Scrum Master / ProjM
- Monthly Stakeholder updates
- Sprint reviews at end of each iteration (Stakeholders invited)
- Ad-hoc escalations as needed (see escalation paths in [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md))

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

# OctoAcme Project Management Docs

This folder contains the program and process documents used by OctoAcme to centralize project management knowledge. It serves as the single entry point for onboarding new contributors and stakeholders, and provides quick access to core process flows, roles, and delivery practices.

## OctoAcme Project Management Processes Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle that moves work from **initiation → planning → execution → release → retrospective**. In initiation, teams validate the business need and define measurable outcomes via a concise **Project One-pager** (problem, SMART objective, success metrics), align stakeholders, sketch a high-level timeline, and capture early risks and resourcing needs. Once there's a clear decision to proceed, planning turns the initiative into an actionable delivery plan by breaking work into shippable increments, creating a prioritized backlog with acceptance criteria, estimating scope, defining a **Definition of Done**, and mapping dependencies and milestones into a release plan.

Clear ownership and well-defined personas are central to execution. **Project Managers (ProjM)** coordinate delivery, timelines, risk/dependency management, and Stakeholder communications; **Product Managers (PdM)** define outcomes, prioritize the backlog, and measure success; **Developers** implement, test, and collaborate through reviews and estimation; **UX/UI Designers** ensure usability and visual quality; **Data Analysts** instrument and measure success metrics; **Scrum Masters / Agile Coaches** facilitate ceremonies and remove impediments; **QA/Testing** validates acceptance and overall quality; and **Stakeholders** provide input and approvals. See [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for full role definitions. Day-to-day execution is supported by an explicit workflow using a project board (e.g., GitHub Projects) with typical states like **Backlog, Ready, In Progress, In Review, QA, Done**, plus a PR workflow emphasizing small changes, linking issues and acceptance criteria, CI checks before review, and at least one approval prior to merge (or a team-defined policy).

Communication is structured around consistent cadence and clear escalation paths. OctoAcme uses a team rhythm of **daily standups** (progress/blockers/dependencies), a **weekly delivery sync** to review progress and risks, and **end-of-sprint demos/reviews**. Stakeholder communications are reinforced with a weekly status update template (progress, next steps, risks/blockers, asks/decisions) and a "single source of truth" for status (such as a project README or release doc). Risk management is maintained through a simple **risk register** (impact/likelihood/owner/mitigation/status) reviewed regularly, with escalation flowing **team → ProjM → PdM → Sponsor/Stakeholder**, and separate handling guidance for security incidents.

Quality assurance is built into both delivery and release practices. During execution, teams expect **unit tests** for new logic, **integration tests** where needed, and **end-to-end smoke tests** for critical flows before release, alongside **security scanning in CI** and manual QA for feature acceptance when appropriate. Releases follow defined pre-release requirements (acceptance criteria met, CI/security checks passing, release notes drafted, rollback/mitigation plan in place, smoke tests ready) and a deployment checklist that emphasizes staging validation, post-deploy verification, and Stakeholder/support announcements. Finally, OctoAcme treats retrospectives as a core operating habit—capturing what went well, what to improve, and a small set of owned action items that feed back into the backlog and are reviewed in ongoing ProjM syncs.

## Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's ProjM lifecycle and principles |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate, scope, and kick off a new initiative |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into a delivery plan and backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflow, board states, PR process, and standups |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and Stakeholder communication cadence |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retros and feeding action items back into the backlog |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions, responsibilities, and expectations for all roles |
| [RACI / Ownership Matrix Template](octoacme-raci-matrix-template.md) | Template for mapping roles to activities and clarifying ownership |

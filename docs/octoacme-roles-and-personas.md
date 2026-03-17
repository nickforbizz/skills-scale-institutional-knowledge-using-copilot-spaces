# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It is the **canonical source** for role definitions; all other process docs reference roles using the abbreviations defined here.

**Abbreviations used across all process docs:**
- **ProjM** — Project Manager
- **PdM** — Product Manager

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers (PdM)

### Role Summary
Product Managers (PdM) define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with Stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with ProjM and engineering leads
- Roadmap updates and Stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers (ProjM)

### Role Summary
Project Managers (ProjM) coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and Stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across Stakeholders

### Typical Communication
- Weekly status updates and Stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX/UI Designer

### Role Summary
UX/UI Designers focus on user experience and visual design, ensuring solutions are intuitive, usable, and visually aligned with the brand. They bridge user needs with technical implementation.

### Responsibilities
- Translate requirements and feedback into wireframes, mockups, and prototypes
- Run usability studies and gather user input
- Collaborate with Developers and PdM throughout development
- Contribute to acceptance criteria related to user experience
- Maintain a shared design system and component library

### Goals
- Deliver clear, accessible, and consistent user interfaces
- Reduce user friction and support task completion
- Ensure design feasibility is validated with Developers early

### Typical Communication
- Design reviews with PdM and Developers
- Usability test findings shared with the full delivery team
- Async feedback via design tool comments (e.g., Figma)

### Interactions with Other Roles
- **PdM**: Collaborates on feature specs and acceptance criteria; PdM provides priorities and user context
- **Developers**: Reviews feasibility of designs; pairs during implementation to catch UX gaps early
- **ProjM**: Flags design dependencies or blockers in sprint planning and standups
- **Stakeholders**: Presents prototypes for feedback at key review checkpoints

---

## Data Analyst

### Role Summary
Data Analysts ensure product and project decisions are informed by data and that outcomes are measured effectively. They translate raw signals into actionable insights for the team.

### Responsibilities
- Define, set up, and maintain product analytics and dashboards
- Analyze user behavior and feature usage
- Translate analysis into actionable insights for the team
- Validate success metrics during and after feature release
- Partner with Developers to instrument key events

### Goals
- Provide timely, reliable data to guide prioritization decisions
- Surface leading indicators of success or failure early
- Enable data-driven retrospectives and continuous improvement

### Typical Communication
- Insight summaries shared with PdM and ProjM at sprint reviews
- Dashboard links and metric definitions documented in the project repo
- Ad-hoc analysis requests via project board or direct message

### Interactions with Other Roles
- **PdM**: Advises on progress toward success metrics; helps refine or challenge metric definitions
- **ProjM**: Reports on project health signals; flags metric regressions or data gaps
- **Developers**: Partners to instrument key events and ensure data pipeline reliability
- **Stakeholders**: Presents outcome data at milestone reviews and release readouts

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master (or Agile Coach) facilitates agile ceremonies, removes impediments, and coaches the team in best practices for iterative delivery. They protect team focus and promote a culture of continuous improvement.

### Responsibilities
- Plan and facilitate sprint ceremonies (standups, sprint planning, reviews, retrospectives)
- Track sprint progress and surface blockers early
- Remove or escalate impediments that the team cannot resolve
- Coach team members on agile practices and collaboration norms
- Promote continuous improvement through retrospective action items

### Goals
- Maximize team velocity and predictability
- Foster a psychologically safe, collaborative team environment
- Reduce cycle time and eliminate waste in delivery processes

### Typical Communication
- Daily standup facilitation and impediment log updates
- Sprint review summaries shared with Stakeholders
- Retrospective action items tracked in the project backlog

### Interactions with Other Roles
- **ProjM**: Partners on schedule, risk, and escalation paths; the Scrum Master surfaces blockers for ProjM to escalate externally
- **PdM**: Ensures the backlog is groomed and priorities are clear before sprint planning
- **Developers**: Shields the team from distractions and helps resolve internal blockers
- **Stakeholders**: Facilitates sprint reviews and ensures Stakeholder feedback is captured

---

## Stakeholder

### Role Summary
Stakeholders provide critical input, feedback, or approvals and represent business, customer, or regulatory needs. They are accountable for the outcomes the project is expected to deliver.

### Responsibilities
- Review deliverables at key project stages
- Provide timely feedback and clarify business expectations
- Approve milestones, releases, or scope changes as needed
- Champion the project within their part of the organization

### Goals
- Ensure the project delivers the expected business or customer value
- Surface organizational constraints or priorities early
- Stay informed without being required at every delivery meeting

### Typical Communication
- Monthly (or milestone-based) status updates from ProjM
- Invited to sprint reviews and milestone demos
- Approval requests via project board, email, or async doc comments

### Interactions with Other Roles
- **PdM**: Primary contact for scope, priority, and outcome decisions
- **ProjM**: Receives regular status reports and escalations
- **Data Analyst**: Reviews outcome data presented at milestone readouts
- **Scrum Master / Agile Coach**: Invited to sprint reviews to provide feedback

---

## Role Interaction Map

The table below summarizes the key collaboration points between roles. Use this as a quick-reference when onboarding new team members or planning a project kick-off.

| | Developers | PdM | ProjM | UX/UI Designer | Data Analyst | Scrum Master | Stakeholder |
|---|---|---|---|---|---|---|---|
| **Developers** | — | Feature specs, AC | Planning, blockers | Design feasibility reviews | Event instrumentation | Daily standups | — |
| **PdM** | Feature specs, AC | — | Weekly sync | Feature scope, usability | Metric definition, readouts | Backlog grooming | Scope & priority decisions |
| **ProjM** | Planning, blockers | Weekly sync | — | Dependency tracking | Health metrics | Impediment escalation | Status reports, approvals |
| **UX/UI Designer** | Design feasibility reviews | Feature scope, usability | Dependency tracking | — | — | Sprint reviews | Prototype feedback |
| **Data Analyst** | Event instrumentation | Metric definition, readouts | Health metrics | — | — | Sprint reviews | Outcome readouts |
| **Scrum Master** | Daily standups | Backlog grooming | Impediment escalation | Sprint reviews | Sprint reviews | — | Sprint reviews |
| **Stakeholder** | — | Scope & priority decisions | Status reports, approvals | Prototype feedback | Outcome readouts | Sprint reviews | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-raci-matrix-template.md`](octoacme-raci-matrix-template.md) for a RACI/Ownership Matrix template that maps these roles to project activities.


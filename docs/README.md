# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation. This README is your starting point for understanding how OctoAcme runs projects and where to find each process guide.

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle designed for clear ownership and iterative delivery. Work typically moves through five stages: **Initiation** (confirm the problem, stakeholders, and success metrics), **Planning** (turn the approved initiative into a prioritized, estimated backlog with dependencies and a Definition of Done), **Execution** (deliver work in small, testable increments), **Release** (deploy with risk controls and verification), and **Close/Retrospective** (capture learnings and convert them into actionable improvements). Key artifacts—such as a Project One-pager/Charter, backlog with acceptance criteria, a risk register, and retrospective action items—provide a consistent source of truth across all stages.

Roles are clearly defined to avoid ambiguity and bottlenecks. **Project Managers (PMs)** coordinate delivery, schedules, risks, and cross-team communication; **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success; **Developers** design and implement changes with tests and documentation; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** supply input and approvals. This separation of responsibilities emphasizes clear decision-making and accountability while keeping execution collaborative through planning sessions, reviews, and ongoing risk management.

Execution is structured around predictable team rhythm and transparent tracking. OctoAcme uses a project board workflow with states like **Backlog → Ready → In Progress → In Review → QA → Done**, supported by regular ceremonies: short daily standups for blockers and dependencies, weekly delivery syncs to review progress and risks, and demos/reviews at the end of sprints or milestones. Stakeholder communication is intentionally standardized through regular updates (weekly or milestone-based) and reusable templates covering progress, next steps, risks/blockers, and decisions needed—with clear escalation paths when business impact warrants it.

Quality assurance and release practices are treated as first-class parts of delivery rather than afterthoughts. PRs are expected to be small when possible, linked to issues and acceptance criteria, and validated via CI (tests, linting, and security scanning) before review; merges typically require at least one approval based on team policy. Testing expectations include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows—especially before production release. Releases also follow explicit pre-release requirements (acceptance criteria met, CI/security checks passing, release notes, rollback plan, and smoke tests), plus post-deploy verification and clear incident/rollback procedures when deployments go wrong.

## Process Lifecycle

1. **Initiation** — Confirm the business need, stakeholders, success metrics, and go/no-go decision.
2. **Planning** — Build a prioritized, estimated backlog; define milestones, dependencies, and Definition of Done.
3. **Execution & Tracking** — Deliver work in small, testable increments; track progress on the project board.
4. **Release & Deployment** — Deploy with risk controls, smoke tests, release notes, and a rollback plan.
5. **Risk Management & Communication** — Maintain the risk register; provide regular stakeholder updates and escalate as needed.
6. **Retrospective & Continuous Improvement** — Capture learnings; convert action items into backlog improvements.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation](octoacme-project-initiation.md) | Validating and authorizing work; One-pager template and initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint delivery, project board workflow, and daily/weekly ceremonies |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and stakeholder communication templates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, post-deploy verification, and rollback |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and process improvement loop |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |

## How to Use These Docs

- **Starting a new project?** Begin with the [Project Initiation](octoacme-project-initiation.md) guide and complete the One-pager/Charter before moving to planning.
- **In active delivery?** Keep the project board up to date and use the [Execution & Tracking](octoacme-execution-and-tracking.md) guide to run standups and weekly syncs.
- **Managing risk?** Keep the risk register current and follow the escalation paths in [Risks & Communication](octoacme-risks-and-communication.md).
- **Preparing a release?** Work through the pre-release checklist and rollback plan in [Release & Deployment](octoacme-release-and-deployment.md).
- **Wrapping up?** Run a retrospective using the format in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) and make sure action items land in the backlog.
- **New to OctoAcme roles?** Review [Roles & Personas](octoacme-roles-and-personas.md) to understand decision ownership and communication expectations.

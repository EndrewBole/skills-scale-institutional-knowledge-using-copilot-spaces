# Project Management Process Overview

Purpose: Provide a single-page summary of the program/project management lifecycle, owners, and escalation paths so teams can quickly find who to contact and how decisions are made.

Owner: Program Operations

## Scope and Applicability

Applies to all cross-functional projects and initiatives at OctoAcme that deliver product features, services, or integrations. All project leads and contributing teams are expected to follow this process.

## Lifecycle Stages

| Stage | Description | Owner |
|---|---|---|
| **Initiation** | Validate business need, confirm stakeholders, define success metrics, and obtain go/no-go approval. | Project Sponsor + Project Lead |
| **Planning** | Build a prioritized, estimated backlog with milestones, dependencies, and a Definition of Done. | Project Lead + Product Manager |
| **Execution & Tracking** | Deliver work in small, testable increments; track progress on the project board; run daily standups and weekly syncs. | Project Lead + Developers |
| **Release & Deployment** | Deploy with risk controls, smoke tests, release notes, and a rollback plan. | Release Manager |
| **Retrospective** | Capture learnings; convert action items into backlog improvements. | Project Lead (facilitated) |

## Decision Owners and RACI

| Decision | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Project approval (go/no-go) | Project Lead | Project Sponsor | Stakeholders, PdM | All team members |
| Scope change | Project Lead | Project Sponsor | PdM, Developers | Stakeholders |
| Release approval | Release Manager | Project Sponsor | QA, Security | All stakeholders |
| Risk escalation (critical) | Project Lead | Project Sponsor | Program Operations | All team members |
| Process document change | Document Owner | Program Operations | Stakeholders | All contributors |

## Risk Escalation Path

All identified risks must be logged in the project risk register.

| Severity | Definition | Who to Contact | Timeline |
|---|---|---|---|
| **Minor** | Low likelihood and low impact; manageable by the team. | Project Lead | Address within current sprint/cycle |
| **Major** | Medium likelihood or significant impact on scope, schedule, or budget. | Project Lead → Project Sponsor | Escalate within 2 business days |
| **Critical** | High likelihood or severe impact (e.g., security, compliance, large cost overrun). | Project Lead → Project Sponsor → Program Operations | Escalate immediately (same business day) |

Steps for escalation:
1. Log the risk in the risk register with severity, likelihood, impact, and proposed mitigation.
2. Notify the appropriate owner based on the severity table above.
3. Agree on a mitigation or contingency plan and assign an owner.
4. Track resolution status in the risk register and report in weekly sync.

## Communication Cadence and Artifacts

| Artifact / Ceremony | Frequency | Audience | Owner |
|---|---|---|---|
| Daily standup | Daily (or async update) | Delivery team | Project Lead |
| Weekly delivery sync | Weekly | PM, PdM, Leads | Project Lead |
| Stakeholder status report | Weekly or milestone-based | Stakeholders | Project Lead |
| Steering committee update | Monthly | Sponsors, Program Ops | Program Operations |
| Risk register | Ongoing | All | Project Lead |
| Retrospective notes | End of sprint/milestone | All team members | Project Lead |

## How to Propose Changes to Process Docs

To suggest an update to any process document:
1. Use the [Process Change Request template](../templates/process-change-request.md) to document the proposed change.
2. Open a GitHub issue referencing the template and the document to change.
3. Assign an owner to implement the changes in `docs/` and open a PR linking the issue.
4. Reviewer(s) approve, then merge and announce the update.

## Related Checklists

- [Project Initiation Checklist](../checklists/initiation-checklist.md)
- [Release & Deployment Checklist](../checklists/release-checklist.md)

## Acceptance Criteria

- Clear owners for each lifecycle stage ✓
- At least one explicit escalation path for risks (minor, major, critical) ✓
- Link to the initiation and release checklists ✓

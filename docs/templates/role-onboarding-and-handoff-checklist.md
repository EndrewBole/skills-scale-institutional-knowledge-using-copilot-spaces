# Role Onboarding and Handoff Checklist

Use this checklist when **onboarding a new contributor** to a project or **handing off a role** (e.g., a new PM joins, or the project transfers to a Support team for sustained engineering). Adapt the items to match your specific role and project context.

---

## Part 1 — Documentation Reading List

Complete before your first week sync or handoff meeting.

- [ ] Read the [Project Management Overview](../octoacme-project-management-overview.md) to understand OctoAcme's delivery approach.
- [ ] Read [Roles and Personas](../octoacme-roles-and-personas.md) to understand how your role interacts with others.
- [ ] Review the completed [Role Interaction Matrix](role-interaction-matrix.md) for this project to see where you are R/A/C/I.
- [ ] Read the [Project Initiation](../octoacme-project-initiation.md) doc and the current Project Charter / One-pager.
- [ ] Review the [Project Planning](../octoacme-project-planning.md) doc and current sprint/iteration backlog.
- [ ] Review the [Risks and Communication](../octoacme-risks-and-communication.md) doc and open Risk Register entries.
- [ ] Review the [Release and Deployment](../octoacme-release-and-deployment.md) doc and latest deployment runbook.
- [ ] Review the most recent [Retrospective notes](../octoacme-retrospective-and-continuous-improvement.md) and open action items.

---

## Part 2 — Access and Tooling

Confirm the following access is provisioned before the handoff is complete.

- [ ] Code repository (read + write as appropriate for the role)
- [ ] Project board (e.g., GitHub Projects, Jira, Linear)
- [ ] Communication channels (Slack/Teams: list relevant channels below)
  - `#project-<name>` general channel
  - `#project-<name>-releases` (if applicable)
  - `#incidents` or escalation channel
- [ ] CI/CD pipeline and deployment tooling (view + trigger permissions)
- [ ] Observability dashboards (e.g., Grafana, Datadog)
- [ ] Design tool access (e.g., Figma) — for UX/UI Designer or PdM
- [ ] Analytics / data warehouse access — for Data Analyst
- [ ] Secret / credentials manager — for Security Engineer or Release Engineer
- [ ] Customer support platform (e.g., Zendesk, GitHub Issues) — for Customer Support

---

## Part 3 — Key Contacts

Identify and introduce yourself to the following people within your first week.

- [ ] Project Manager (PM): `@_______`
- [ ] Product Manager (PdM): `@_______`
- [ ] Tech Lead / Senior Developer: `@_______`
- [ ] QA Lead: `@_______`
- [ ] UX/UI Designer: `@_______`
- [ ] Data Analyst: `@_______`
- [ ] Security Engineer: `@_______`
- [ ] Customer Support lead: `@_______`
- [ ] Release Engineer: `@_______`
- [ ] Primary Stakeholder / Sponsor: `@_______`

---

## Part 4 — Meetings to Join

Ensure you are added to the following recurring meetings.

- [ ] Weekly PM + PdM alignment sync
- [ ] Sprint/iteration planning
- [ ] Daily or twice-weekly team standup
- [ ] Release readiness review (before each deployment window)
- [ ] Monthly stakeholder update
- [ ] Retrospective (end of each iteration)

---

## Part 5 — Handoff-Specific Steps

Complete these steps when transitioning a role to a new person (as opposed to simply onboarding a new team member).

### Outgoing role holder
- [ ] Provide a written summary of current project status, open decisions, and outstanding action items.
- [ ] Walk through the Risk Register and flag any high-priority items verbally.
- [ ] Share context on stakeholder relationships, sensitivities, and communication preferences.
- [ ] Transfer ownership of all project boards, documents, and shared credentials to the incoming role holder.
- [ ] Schedule a minimum 30-minute knowledge-transfer session with the incoming person.
- [ ] Introduce the incoming person to all key contacts listed in Part 3.
- [ ] Confirm all access provisioning from Part 2 is complete for the incoming person.
- [ ] Remain available for questions for at least two weeks post-handoff (or agree on a shorter window with PM).

### Incoming role holder
- [ ] Complete Parts 1–4 of this checklist before the handoff meeting.
- [ ] Attend the knowledge-transfer session with the outgoing role holder.
- [ ] Review and accept ownership of open action items; close or reassign any that are no longer relevant.
- [ ] Send an introduction message to the project communication channel.
- [ ] Confirm your understanding of the current scope, schedule, and top risks with the PM.

---

## Part 6 — Handoff Sign-off

Both parties should confirm completion before the handoff is considered closed.

| Item | Outgoing | Incoming | Date |
|---|---|---|---|
| Documentation reading complete | ☐ | ☐ | |
| Access provisioned and verified | ☐ | ☐ | |
| Key contacts introduced | ☐ | ☐ | |
| Open items transferred | ☐ | ☐ | |
| Knowledge-transfer session held | ☐ | ☐ | |
| Handoff complete | ☐ | ☐ | |

> Store the completed checklist in the project repository or project wiki so there is an audit trail of the handoff.

# Role Interaction Matrix (RACI-style)

Use this template during kickoff and planning to record who is Responsible, Accountable, Consulted, and Informed for key project activities. Copy this table into your project repo and update the cells for your team.

Legend:
- R = Responsible (does the work)
- A = Accountable (owns the outcome/decision)
- C = Consulted (subject-matter input)
- I = Informed (needs to be kept up-to-date)

| Activity / Role | PM | PdM | Developers | QA | UX/UI Designer | Data Analyst | Security Engineer | Release Engineer | Support / Advocacy |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Initiation / One-pager | A | R | I | I | C | C | I | I | I |
| Planning / Backlog Prioritization | R | A | C | C | C | C | I | I | I |
| Design / Prototyping | I | C | C | I | R | C | I | I | I |
| Implementation / Development | I | C | R | C | C | I | C | I | I |
| QA / Acceptance | I | I | C | R | C | I | I | I | I |
| Release Planning | R | A | C | C | I | I | I | R | I |
| Monitoring & Analytics | I | I | C | I | I | R | I | I | C |
| Security Review & Sign-off | I | I | C | I | I | I | R | I | I |
| Support Handoff / Knowledge Transfer | R | C | C | I | I | I | I | I | A |

Example: Release Planning
- Guidance: In the Release Planning row above, the PM is Responsible for coordinating the release activities, the PdM is Accountable for timing and scope decisions, the Release Engineer is Responsible for pipelines and execution, Developers are Consulted for cutover and migrations, and Support is Informed and will own immediate post-release customer communication.
- Use during planning: review this matrix at kickoff, confirm cells with stakeholders, and attach to the project docs for clarity.

How to use:
1. Copy this file into your project docs.
2. Edit roles to match your team (rename/add role columns where needed).
3. Save the completed matrix as part of the project kickoff artifacts and reference it in planning and release docs.

# Role Interaction Matrix Template (RACI)

Use this template to define who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each key project activity.

## RACI Key

| Symbol | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; signs off |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — receives updates after decisions are made |

> Each activity must have exactly **one A** (accountable owner). Multiple R/C/I entries are allowed.

---

## How to use this template

1. Copy the matrix below into your Project Charter or planning document.
2. Replace activity rows with the specific work items relevant to your project.
3. Fill in R / A / C / I for each role column.
4. Review the completed matrix during the **Planning Kickoff** meeting so all roles acknowledge their responsibilities.
5. Update the matrix when team composition or scope changes significantly.

---

## Role Interaction Matrix

| Activity | PM | PdM | Developer | QA | UX/UI Designer | Data Analyst | Security Engineer | Customer Support | Release Engineer | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| **Initiation & Charter** | A | C | I | I | I | I | C | I | I | C |
| **Release Planning** *(example)* | A | C | C | C | C | I | C | C | R | I |
| **Design & Prototyping** | I | C | C | C | A/R | I | C | C | I | C |
| **Implementation** | I | C | A/R | C | C | I | C | I | C | I |
| **QA & Testing** | I | C | R | A/R | C | I | C | I | C | I |
| **Security Review** | C | C | C | C | I | I | A/R | I | C | I |
| **Release & Deployment** | C | I | C | C | I | I | C | C | A/R | I |
| **Customer Communication** | I | C | I | I | I | I | I | A/R | I | C |
| **Analytics & Metrics Review** | I | C | C | I | I | A/R | I | I | I | C |
| **Retrospective** | A/R | C | R | R | R | C | C | C | C | I |

> **Release Planning example row explained:**
> The PM is *Accountable* (owns the release plan and schedule). The Release Engineer is *Responsible* (creates the deployment runbook and pipeline). PdM, Developers, QA, UX/UI Designer, and Security Engineer are *Consulted* for input. Data Analyst, Customer Support, and Stakeholders are *Informed* of the agreed plan.

---

## Customising this matrix

- Add or remove rows to match your project's activities.
- Add or remove role columns to reflect the actual team composition.
- For large programmes, consider a separate matrix per workstream.
- Store the completed matrix alongside your [Project Charter](../octoacme-project-initiation.md) and link it from the project board.

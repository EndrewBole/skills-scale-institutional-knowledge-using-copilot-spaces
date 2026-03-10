# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

**How to use personas in project artifacts:** Reference these persona definitions when assigning owners in a Project Charter, populating a RACI matrix, or writing acceptance criteria that involve multiple roles. Each persona can also be used as a persona prompt in Copilot Spaces to shape role-specific guidance. For a full view of how roles interact across project activities, see the [Role Interaction Matrix template](templates/role-interaction-matrix.md).

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

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX/UI Designer

### Role Summary
UX/UI Designers translate product requirements and user research into intuitive, accessible interfaces. They advocate for the end user throughout the design and development process.

### Responsibilities
- Produce wireframes, prototypes, and final design specifications
- Conduct or synthesize user research and usability testing
- Maintain a consistent design system and component library
- Review implemented UIs for fidelity to design intent
- Participate in acceptance criteria definition for user-facing features

### Goals
- Deliver usable, accessible, and visually consistent experiences
- Reduce friction and support tickets caused by poor UX
- Shorten feedback loops between design and engineering

### Typical Communication
- Design reviews and critique sessions with Developers and PdM
- Annotated prototypes shared in design tools (e.g., Figma)
- Usability findings summarized in brief research reports

### Interactions
- **PM**: keeps PM informed of design timeline dependencies and flags scope changes that affect scheduling.
- **PdM**: collaborates closely on user stories and acceptance criteria; PdM prioritizes the design backlog.
- **Developers**: hands off detailed specs and assets; participates in implementation reviews to maintain design fidelity.
- **QA**: coordinates on usability and accessibility test cases; QA flags visual regressions during test cycles.
- **Stakeholders**: presents prototypes for early feedback; manages design-change requests through PdM sign-off.

---

## Data Analyst

### Role Summary
Data Analysts define, collect, and interpret metrics that measure product performance and project outcomes. They surface insights that guide prioritization and continuous improvement.

### Responsibilities
- Define success metrics and key performance indicators (KPIs) for features and projects
- Build and maintain dashboards and reports for stakeholder consumption
- Investigate anomalies and surface actionable insights
- Partner with Developers and PdM on instrumentation and data collection requirements
- Support retrospectives with quantitative evidence of improvement or regression

### Goals
- Enable data-driven decisions across product and project teams
- Reduce time-to-insight for key business and quality metrics
- Improve instrumentation coverage so impact is measurable

### Typical Communication
- Weekly or bi-weekly metrics reviews with PdM and PM
- Dashboard links and written insight summaries in project channels
- Ad-hoc analysis requests documented as tickets

### Interactions
- **PM**: provides project-health metrics and flags data-driven risks during planning.
- **PdM**: partners on defining success metrics before features ship; validates impact post-launch.
- **Developers**: works with engineering on event tracking and data pipeline requirements.
- **QA**: cross-references quality metrics (defect rates, test coverage) to support release readiness reviews.
- **Stakeholders**: delivers executive-ready summaries and trend analyses at milestone reviews.

---

## Security Engineer

### Role Summary
Security Engineers identify, assess, and mitigate security risks across the product and infrastructure. They embed security practices into every phase of the development lifecycle.

### Responsibilities
- Conduct threat modeling and security design reviews at project initiation and planning
- Perform or coordinate vulnerability assessments and penetration testing
- Define and enforce secure coding standards and dependency policies
- Review pull requests for security-relevant changes
- Manage security incidents and drive remediation to closure
- Maintain compliance documentation and audit trails

### Goals
- Reduce exploitable vulnerabilities before reaching production
- Establish security as a shared responsibility across the team
- Minimize mean time to detect and remediate security issues

### Typical Communication
- Security review outcomes documented in the project Risk Register
- Findings shared as security-tagged tickets or comments in code reviews
- Escalations routed through PM to stakeholders when risk is high

### Interactions
- **PM**: surfaces security risks and required activities in the project Risk Register; aligns remediation timelines with the project schedule.
- **PdM**: consulted during feature scoping to ensure privacy and compliance requirements are captured.
- **Developers**: collaborates on secure design patterns, reviews PRs, and advises on library/dependency choices.
- **QA**: coordinates security-specific test cases (e.g., auth, injection); reviews automated security scan results.
- **Stakeholders**: informs stakeholders of significant security findings and compliance status at key milestones.

---

## Customer Support / Advocacy

### Role Summary
Customer Support and Advocacy representatives are the voice of the customer within the team. They collect and escalate product pain points, manage user-facing communications around releases, and ensure customers have a positive experience throughout the product lifecycle.

### Responsibilities
- Triage and escalate customer-reported issues to the appropriate team
- Document known issues and workarounds in the support knowledge base
- Participate in release planning to anticipate support load and prepare communications
- Provide the team with qualitative customer feedback and recurring issue patterns
- Coordinate customer-facing release notes and change communications

### Goals
- Reduce support ticket volume through proactive communication and quality improvements
- Shorten time-to-resolution for customer-impacting issues
- Ensure customers are informed and confident in product changes

### Typical Communication
- Weekly support-summary reports shared with PdM and PM
- Pre-release coordination meetings to review known issues and rollout plans
- Escalation paths documented for critical customer-impacting bugs

### Interactions
- **PM**: flags customer-impacting risks before and during release; PM coordinates escalation resolutions.
- **PdM**: provides qualitative customer data that feeds backlog prioritization; PdM keeps Support informed of upcoming changes.
- **Developers**: escalates critical bugs with reproduction steps and customer context; collaborates on hotfix prioritization.
- **QA**: coordinates on regression testing for frequently reported issues; QA shares test results to confirm fixes before customer communication.
- **Stakeholders**: represents the customer perspective in milestone reviews; prepares customer communications with stakeholder approval.

---

## Release Engineer

### Role Summary
Release Engineers own the build, packaging, and deployment pipelines. They ensure releases are reproducible, auditable, and can be safely rolled back when needed.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and release automation
- Define and enforce branching strategies, version schemes, and release gates
- Coordinate release schedules and deployment windows with PM and stakeholders
- Manage environment configurations and infrastructure-as-code changes for releases
- Produce release artifacts, changelogs, and deployment runbooks
- Lead rollback procedures and post-incident release reviews

### Goals
- Achieve zero-downtime, one-click deployments with high confidence
- Reduce lead time from code-complete to production
- Ensure every release is auditable and reversible

### Typical Communication
- Release readiness reports shared with PM, QA, and Developers before each deployment
- Deployment runbooks linked from project boards or wikis
- Post-deployment status updates to PM and Stakeholders

### Interactions
- **PM**: aligns on deployment windows and release schedule; PM uses release readiness reports to confirm go/no-go decisions.
- **PdM**: coordinates on feature-flag strategies and phased rollouts to manage customer impact.
- **Developers**: enforces branching standards and reviews infrastructure-impacting code changes; guides Developers on release tooling.
- **QA**: receives go/no-go signal from QA before deployment; coordinates environment provisioning for test cycles.
- **Stakeholders**: provides deployment status and rollback readiness confirmation at release milestones.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning work items or defining ownership in a Project Charter, map each activity to one or more of these personas using the [Role Interaction Matrix template](templates/role-interaction-matrix.md).
- When onboarding a new team member or handing off a role, use the [Role Onboarding and Handoff Checklist](templates/role-onboarding-and-handoff-checklist.md).


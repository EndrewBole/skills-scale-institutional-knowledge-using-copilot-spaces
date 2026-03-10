# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Use these persona definitions when creating project artifacts (project one-pagers, kickoff notes, RACI/interaction matrices) to clearly identify who owns work, who is consulted, and who should be informed. For team planning, use the Role Interaction Matrix template in docs/templates/role-interaction-matrix.md to map responsibilities across activities; use docs/templates/role-onboarding-and-handoff-checklist.md for smooth transitions and onboarding.

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

### Interactions
- Work directly with Product Managers on feature requirements and acceptance criteria.
- Coordinate with QA for test plans and acceptance verification.
- Engage with Release Engineers for deployment pipelines and schedules.

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

### Interactions
- Partner with Developers to clarify scope and acceptance criteria.
- Coordinate with UX/UI Designers to validate designs and research findings.
- Consult Data Analysts to define and interpret success metrics.

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

### Interactions
- Liaise with Product Managers to align delivery timeline with product priorities.
- Coordinate handoffs between Developers, QA, and Release Engineers.
- Use the Role Interaction Matrix during planning to clarify responsibilities.

---

## Additional Personas (new)

---

## UX/UI Designer

### Role Summary
Designs user experiences and interfaces to meet user needs and product requirements.

### Responsibilities
- Conduct user research, usability testing, and synthesize findings
- Produce wireframes, prototypes, and UI specifications
- Define accessibility and usability acceptance criteria
- Collaborate with Product and Development to iterate on designs

### Goals
- Improve ease-of-use and user satisfaction
- Reduce rework caused by misaligned design and implementation
- Ensure accessibility and consistency across product surfaces

### Typical Communication
- Design reviews, user research reports, and design artifacts (Figma, UX docs)
- Syncs with Product and Developers during planning and implementation

### Interactions
- Works with Product Managers to shape requirements and success metrics.
- Provides designs and specs to Developers and QA and participates in design reviews.
- Coordinates with Data Analysts to validate design decisions using analytics.

---

## Data Analyst

### Role Summary
Analyzes product data and metrics to guide decision-making and measure success.

### Responsibilities
- Define tracking requirements and success metrics for features
- Build dashboards and run analyses to surface trends and regressions
- Validate A/B tests and experiments; present findings with recommendations
- Ensure instrumentation and data quality

### Goals
- Provide timely, actionable insights to inform product decisions
- Reduce uncertainty with quantitative evidence
- Improve measurement coverage and reliability

### Typical Communication
- Dashboards, analysis notes, and metric definitions
- Regular syncs with Product and Project leads for metric reviews

### Interactions
- Works with Product Managers to define success metrics and KPIs.
- Coordinates with Developers to ensure proper instrumentation is implemented.
- Provides input to PMs and Designers to prioritize experiments and iterations.

---

## Security Engineer

### Role Summary
Ensures product security through risk assessment, secure design review, and compliance monitoring.

### Responsibilities
- Conduct security reviews and threat modeling for features and architecture
- Lead vulnerability assessments, code reviews for security, and incident response
- Define security acceptance criteria and compliance checklists
- Maintain secure-by-default guidance and training for teams

### Goals
- Reduce security risk and ensure compliance with applicable standards
- Enable secure development practices without blocking delivery unnecessarily

### Typical Communication
- Security review notes, vulnerability reports, and incident briefings
- Ad-hoc consultations during design and planning

### Interactions
- Collaborates with Developers on secure implementation and remediation of findings.
- Works with Project Managers and Product Managers to communicate security risks and required mitigations.
- Engages with Release Engineers on safe deployment practices and emergency rollbacks.

---

## Customer Support / Advocacy

### Role Summary
Bridges the gap between users and development by relaying feedback and surfacing issues that impact adoption or satisfaction.

### Responsibilities
- Collect, triage, and communicate user feedback and bug reports
- Maintain knowledge base and support guides relevant to releases
- Advocate for customer needs during prioritization and release planning
- Participate in incident response and customer communication

### Goals
- Improve customer satisfaction and reduce time-to-resolution for user issues
- Ensure customer-facing documentation is accurate and timely

### Typical Communication
- Support tickets, trend reports, and customer impact summaries
- Close collaboration with Product and Engineering during incidents and releases

### Interactions
- Provides prioritized feedback to Product Managers and Project Managers.
- Works with Developers and QA on reproducing and validating fixes.
- Coordinates with Release Engineers and PMs for release communications and escalation.

---

## Release Engineer

### Role Summary
Owns build, deployment, and release automation ensuring smooth and reliable launches.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Automate environment provisioning and rollback strategies
- Monitor deployment health and lead deployment verification activities
- Collaborate on release notes and release runbooks

### Goals
- Reduce manual release steps and deployment risk
- Improve deployment speed and reliability

### Typical Communication
- Pipeline and deployment runbook documentation, incident logs, and release notes
- Syncs with Developers, QA, and PMs prior to release windows

### Interactions
- Works with Developers to troubleshoot build and deployment issues.
- Coordinates with Project Managers and Product Managers on release windows and communication.
- Engages with Customer Support for post-release monitoring and communication.

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
- For planning and kickoff, complete the Role Interaction Matrix (docs/templates/role-interaction-matrix.md) to make RACI-style ownership explicit across major activities.

# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Use these persona definitions when creating project artifacts (project one-pagers, kickoff notes, RACI/interaction matrices) to clearly identify who owns work, who is consulted, and who should be informed. For team planning, use the Role Interaction Matrix template in docs/templates/role-interaction-matrix.md to map responsibilities across activities; use docs/templates/role-onboarding-and-handoff-checklist.md for smooth transitions and onboarding.

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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For planning and kickoff, complete the Role Interaction Matrix (docs/templates/role-interaction-matrix.md) to make RACI-style ownership explicit across major activities.

# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Additional Personas

### Release Engineer

#### Role Summary
Release Engineers ensure releases are automated, safe, and observable. They own CI/CD pipelines, coordinate release windows, and verify post-deployment health.

#### Responsibilities
- Own and maintain CI/CD pipelines and release automation
- Create and enforce release checklists and procedures
- Coordinate release windows and deployment scheduling
- Document rollback and mitigation plans
- Run post-deploy verification and smoke tests
- Ensure CI/CD hygiene and best practices are followed

#### Goals
- Minimize deployment risk and time-to-production
- Reduce manual toil in release processes
- Ensure rapid, safe rollback capability
- Maintain observability throughout releases

#### Typical Communication
- Coordinate with Project Manager on release timing and windows
- Work with Developers on CI/CD pipeline changes and improvements
- Collaborate with QA on test automation and verification
- Partner with SRE/On-call for monitoring and incident response
- Provide release checklists and runbooks to the team

---

### Site Reliability Engineer (SRE)

#### Role Summary
Site Reliability Engineers define and maintain reliability targets, own incident response runbooks, and ensure systems are observable and resilient.

#### Responsibilities
- Define SLAs, SLOs, and error budgets for services
- Design and implement observability (metrics, logs, traces)
- Create and maintain incident response runbooks
- Conduct postmortems and drive reliability improvements
- Plan capacity and scalability
- Review reliability implications of deployments and architecture changes

#### Goals
- Maintain agreed-upon service reliability targets
- Enable fast incident detection and resolution
- Reduce toil through automation and tooling
- Build a culture of blameless postmortems and learning

#### Typical Communication
- Partner with Developers on operability and observability requirements
- Coordinate with Release Engineer on deployment safety and monitoring
- Align with Product/PM on SLA implications and trade-offs
- Escalate critical incidents and coordinate response
- Share postmortem findings and action items with stakeholders

---

### Security Lead (or Security Reviewer)

#### Role Summary
Security Leads perform threat modeling, coordinate security scanning and approvals, and ensure compliance and security best practices are followed throughout the project lifecycle.

#### Responsibilities
- Conduct threat modeling for major features and architecture changes
- Coordinate security scanning and vulnerability assessments in CI
- Review security-sensitive code and approve security changes
- Maintain security checklists and guardrails for releases
- Advise on compliance requirements and data protection
- Escalate to Security on-call for security incidents

#### Goals
- Prevent security vulnerabilities and data breaches
- Ensure compliance with applicable standards and regulations
- Build security into the development process, not as an afterthought
- Reduce security risk and incident response time

#### Typical Communication
- Review PRs for security-sensitive changes and provide guidance
- Advise Product/PM on compliance and security implications
- Collaborate with Developers on secure coding practices
- Coordinate with Release Engineer on security checklist for releases
- Escalate security incidents and coordinate with Security on-call

---

### UX Researcher / Product Designer

#### Role Summary
UX Researchers and Product Designers conduct user research, validate assumptions, create design artifacts, and measure usability outcomes to ensure features are user-centered and effective.

#### Responsibilities
- Conduct user research and validate customer assumptions
- Create wireframes, prototypes, and design specifications
- Perform usability testing and gather feedback
- Measure design and usability outcomes through metrics
- Provide design handoffs to development team
- Iterate on designs based on user feedback and data

#### Goals
- Maximize user satisfaction and adoption
- Reduce support burden through intuitive design
- Validate product decisions through evidence
- Balance customer needs with business constraints

#### Typical Communication
- Collaborate with Product Managers to understand user needs and success metrics
- Provide design artifacts and specifications to Developers
- Participate in implementation and acceptance testing to ensure design fidelity
- Share research findings and usability insights with stakeholders
- Iterate on designs based on user feedback and telemetry

---

### Data Analyst / Analytics Owner

#### Role Summary
Data Analysts and Analytics Owners define success metrics, instrument systems to capture relevant data, own analytics dashboards, and validate outcomes against telemetry.

#### Responsibilities
- Define success metrics and KPIs for projects
- Instrument code to capture relevant events and telemetry
- Build and maintain analytics dashboards and reports
- Analyze data to validate feature success and impact
- Identify trends, anomalies, and insights from telemetry
- Provide data-driven recommendations for iterations

#### Goals
- Enable data-informed decision-making
- Measure and communicate business impact
- Reduce guesswork in prioritization and design
- Support rapid hypothesis testing and validation

#### Typical Communication
- Collaborate with PM and Product on defining success metrics
- Work with Developers on event instrumentation and data quality
- Partner with QA on data validation and test data
- Share dashboards and insights with stakeholders
- Support retrospectives with data on outcomes and impact

---

### Technical Writer / Documentation Owner

#### Role Summary
Technical Writers and Documentation Owners maintain user-facing and internal process documentation, ensuring knowledge is captured, organized, and accessible throughout the project lifecycle.

#### Responsibilities
- Maintain user guides, API documentation, and help content
- Document internal processes, runbooks, and decision logs
- Collaborate with team to capture key decisions and rationale
- Publish release notes and migration guides
- Maintain FAQ and troubleshooting content
- Update documentation with each release

#### Goals
- Reduce support burden through comprehensive documentation
- Enable team knowledge sharing and onboarding
- Maintain a single source of truth for processes and decisions
- Improve user self-service and reduce time-to-value

#### Typical Communication
- Work with Product Managers and Developers to capture feature details
- Coordinate with Release Engineer to publish release notes and migration steps
- Support Customer Success and Support teams with knowledge articles
- Participate in retrospectives to document learnings and action items
- Version control documentation alongside code

---

### Stakeholder Liaison (or Business Sponsor Liaison)

#### Role Summary
Stakeholder Liaisons serve as the primary contact for executive stakeholders, consolidate feedback, clarify business priorities, and ensure stakeholder alignment and acceptance of deliverables.

#### Responsibilities
- Identify and maintain stakeholder list and communication preferences
- Collect and consolidate stakeholder feedback and requirements
- Clarify business priorities and acceptance criteria
- Provide regular stakeholder updates and reports
- Escalate business-critical issues and blockers
- Secure stakeholder sign-off on deliverables and releases

#### Goals
- Maintain stakeholder trust and alignment
- Reduce surprise and misalignment on priorities
- Enable rapid decision-making by surfacing business context
- Ensure business value is delivered and communicated

#### Typical Communication
- Weekly or milestone-based status updates to stakeholders
- Coordinate with Project Manager on communications and escalations
- Align with Product Manager on business priorities and scope decisions
- Provide executive summaries and business impact reports
- Facilitate stakeholder reviews and sign-offs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running projects, identify which personas are needed based on project scope and complexity.
- Use the interaction patterns to clarify handoffs and communication expectations.
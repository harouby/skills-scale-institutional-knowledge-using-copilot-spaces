# OctoAcme Project Management Docs

## Overview

OctoAcme uses a lightweight, iterative project management approach focused on clear ownership, measurable outcomes, and continuous improvement. Our processes guide projects through five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**.

### Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

---

## How OctoAcme Project Management Works

OctoAcme follows a structured lifecycle approach that guides projects from initial concept through completion and continuous improvement. The methodology is organized around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. 

During **initiation**, teams validate business needs by creating a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and timeline. Once stakeholder alignment is confirmed at a decision gate, the project moves into **planning**, where work is broken down into prioritized backlog items with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established. This structured handoff ensures that only well-scoped, understood work enters the execution phase, reducing rework and misalignment.

**Execution** and ongoing delivery are coordinated through a regular team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations using GitHub Projects with standardized columns: Backlog, Ready, In Progress, In Review, QA, and Done. Small pull requests (≤400 lines when possible) with clear issue links and acceptance criteria are the standard unit of work, and all changes must pass automated CI, linting, and security scans before requiring at least one approval. Quality is embedded throughout this phase via unit tests, integration tests, end-to-end smoke tests, and manual QA when needed. Risk management is continuous: blockers are triaged in daily standups (Level 1), escalated to Product Leads and dependent teams (Level 2), or to sponsors for business-impacting issues (Level 3). Progress is tracked using velocity, burndown, and key success metrics defined in the project one-pager.

OctoAcme defines clear **roles and responsibilities** to ensure accountability and smooth collaboration. The **Project Manager** coordinates delivery, manages schedules, risks, and communications; the **Product Manager** defines outcomes and prioritizes the backlog; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates acceptance criteria. Communication is structured around weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations as needed. A single source of truth—typically the project README or status doc—keeps all stakeholders informed of progress, risks, and blockers using consistent templates for weekly status updates and incident communications.

**Release and deployment** are governed by pre-release checklists ensuring all acceptance criteria are met, CI passes, security scans complete, and rollback plans are documented. After each sprint, release, or milestone, teams conduct blameless retrospectives to capture what went well, identify improvements, and convert insights into prioritized action items with owners and due dates. This continuous improvement cycle—combined with measurement of action item impact—reinforces OctoAcme's culture of psychological safety, data-informed decision-making, and iterative delivery of customer value.

---

## Process Documents Index

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, core artifacts, lifecycle phases, and communication cadence
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define initial steps to validate business need, align stakeholders, and create lightweight plans
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable plans and prioritized backlogs
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, workflows, quality standards, and blocker escalation
- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk management, stakeholder communication, and escalation paths
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases, deployment checklists, rollback procedures, and release notes
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Define typical roles (Developers, Product Managers, Project Managers) and responsibilities

---

## How to Use These Docs

### For New Team Members
Start with **Project Management Overview** to understand the framework, then explore specific docs as needed for your role and current phase.

### For Copilot Spaces
Reference these docs by adding them to your Space context to get role-specific guidance and process-aligned recommendations. Add the `.copilot/` folder link in your Space configuration.

### For Project Repos
Link to this README from your project's root README or `.github/` folder so team members can quickly access the canonical OctoAcme processes.

### For Process Improvements
Use the issue template [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates, clarifications, or new content.

---

## Core Lifecycle at a Glance

| Phase | Key Activities | Artifacts |
|-------|----------------|-----------|
| **Initiation** | Validate need, align stakeholders, define success metrics | One-pager, stakeholder list, initial risk register |
| **Planning** | Break work into increments, estimate, identify dependencies | Prioritized backlog, release plan, Definition of Done |
| **Execution** | Build, test, review, iterate with regular demos | PRs, test results, progress tracking |
| **Release** | Deploy to production with pre-release checks and rollback plan | Release notes, deployment verification |
| **Retrospective** | Capture learnings and convert to action items | Retrospective notes, improvement backlog |

---

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + Product Manager sync; Delivery team standups (2x weekly or as agreed)
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Risk escalations and incident communications

---

## Getting Help

- **Process questions?** Refer to the relevant doc above or open an issue using the [Process Doc Update template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Need role-specific guidance?** See [Roles & Personas](octoacme-roles-and-personas.md)

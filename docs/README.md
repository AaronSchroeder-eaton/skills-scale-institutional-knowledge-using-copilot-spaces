# OctoAcme Project Management Docs

Welcome to the OctoAcme project management knowledge base. This repository centralizes all major processes, roles, and practices we use to deliver projects efficiently and consistently.

## Project Management Process Overview

**Project Lifecycle & Governance**

OctoAcme operates projects through a five-stage lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Each stage has clear decision gates and deliverables to ensure alignment before progressing. During Initiation, teams validate business need and create a lightweight Project One-pager that confirms success metrics, stakeholders, and timeline. The Planning phase breaks work into shippable increments with prioritized backlogs, estimated scope, and documented dependencies. This structured approach ensures that only well-defined initiatives move into Execution, reducing waste and rework.

**Core Roles & Communication Structure**

OctoAcme defines three primary personas: Project Managers (who coordinate delivery, schedules, and risk), Product Managers (who define outcomes and prioritize the backlog), and Developers (who implement features collaboratively). The organization emphasizes clear ownership and psychological safety, with weekly syncs between PM and Product Manager, twice-weekly delivery standups, and monthly stakeholder updates. Risk and dependency escalation follows a three-level path from team triage to PM escalation to sponsor involvement, ensuring issues are surfaced and resolved transparently.

**Execution & Quality Standards**

During Execution, teams use GitHub Projects boards with defined columns (Backlog, Ready, In Progress, In Review, QA, Done) and follow a pull request workflow requiring small, reviewable changes, automated testing, and peer approval before merge. Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Teams maintain a Risk Register updated weekly and track velocity, burndown, and success metrics to stay aligned with project goals.

**Release & Continuous Improvement**

OctoAcme standardizes releases by release type (Patch, Minor, Major), requiring passing CI, security scans, smoke tests, and documented rollback plans before deployment. Post-release, teams conduct retrospectives to capture learnings and convert them into actionable improvements tracked in the project backlog. This cycle of measured execution, careful release, and systematic retrospectives creates a culture of continuous improvement and institutional learning across the organization.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, core roles, and key artifacts.
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate, authorize, and prepare for a new project.
- [Project Planning](octoacme-project-planning.md) — How to break work into shippable increments and create an actionable backlog.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, team rhythm, and progress tracking.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized process for releasing features to production.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — How to capture learnings and drive improvements.
- [Roles and Personas](octoacme-roles-and-personas.md) — Definitions of core roles (Developers, Product Managers, Project Managers) and their responsibilities.

---

**Getting Started**

New team members should start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and lifecycle. Then, refer to the specific docs based on your current project phase.

For questions or updates to these processes, please create an issue or pull request referencing the relevant documentation.

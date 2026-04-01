# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This README serves as the entry point for understanding how OctoAcme plans, executes, and continuously improves its projects. Use the index below to navigate to detailed guidance on each phase of our project lifecycle.

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle designed to keep teams aligned while delivering in small, measurable increments. Work moves through **Initiation → Planning → Execution → Release → Close/Retrospective**, with an emphasis on customer value, clear ownership, iterative delivery, and data-informed decisions. Key artifacts support this flow—including a Project Charter/One-pager, roadmap and release plan, sprint/iteration backlog with acceptance criteria, a risk register, and retrospective action items—all kept as living documentation to preserve decisions and reduce single-person dependency.

Roles are clearly defined to support accountability and collaboration. A named **Project Manager (PM)** coordinates delivery (schedule, risks, dependencies, and communications) and ensures consistent documentation and status reporting. A **Product Manager (PdM)** owns outcomes—problem statements, success metrics, and backlog prioritization—while **developers** design, implement, test, and contribute to technical risk management. **QA/Testing** validates quality and acceptance criteria, and **stakeholders** provide input and approvals at key decision points (such as the initiation gate to move from idea to planning).

Execution is organized around a consistent team rhythm and transparent work tracking. Teams use a project board (e.g., GitHub Projects) with workflow states such as Backlog, Ready, In Progress, In Review, QA, and Done, supported by regular ceremonies including short daily standups, weekly PM + PdM alignment syncs, and demos/reviews at sprint or milestone boundaries. Stakeholder updates are provided on a regular cadence using a single source of truth. Risk and dependency management is continuous: risks are identified and assessed throughout the project, tracked in a simple register, reviewed in weekly syncs, and escalated via a defined path from team triage to the PM/Product Lead and, if needed, to sponsor-level escalation.

Quality assurance and release practices are built into the workflow to reduce delivery risk. OctoAcme favors small pull requests (targeting ~400 lines when possible) that include issue links and acceptance criteria, with CI checks (tests, linting, and security scanning) completed before review and at least one approval required before merge. Testing expectations include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows prior to release. Releases follow a standardized checklist—ensuring acceptance criteria are met, release notes and rollback plans exist, staging validations are performed, and post-deploy verification and stakeholder announcements occur—followed by retrospectives that convert lessons learned into owned, time-bound backlog items for continuous improvement.

## Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to Use and Update These Docs

- **New team members:** Start here, then read the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md) to get oriented quickly.
- **Updating docs:** Open a pull request with your proposed changes, link it to the relevant issue, and request a review from your PM or Product Lead. Keep all documents as living references—update them when processes change, not just at project close.
- **Copilot Spaces:** Add or reference these documents in your `.copilot/` configuration to give Copilot context about OctoAcme's processes when using AI-assisted workflows.

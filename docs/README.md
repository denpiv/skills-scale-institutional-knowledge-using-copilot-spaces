# OctoAcme Project Management Docs

This README serves as the entry point to OctoAcme's process documentation for project management. It summarizes how OctoAcme runs cross-functional projects and links to the available process artifacts in this folder.

## Project management processes — brief overview

OctoAcme manages projects through a clear, repeatable lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Work begins with a lightweight Project One‑pager that clarifies the problem, success metrics, stakeholders, and initial milestones. Planning produces a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan so work is broken into shippable increments and dependencies are surfaced early.

Day‑to‑day delivery uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull‑request process: small PRs where possible, CI and security scans run before review, inclusion of issue links and acceptance criteria in PR descriptions, and at least one approval before merging. Risks and cross‑team dependencies are recorded in a Risk Register and reviewed during regular syncs to ensure timely escalation.

Roles are explicit: Project Manager (PM) coordinates delivery, schedules, risks, and stakeholder communications; Product Manager (PdM) defines outcomes and prioritizes the backlog; Developers implement and test; QA validates acceptance criteria; and stakeholders provide input and approvals. Communication cadence includes standups, delivery syncs, demos, and stakeholder updates to keep alignment and surface blockers early.

Quality is enforced across the lifecycle: automated unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, manual QA when needed, and release checklists (staging smoke tests, post‑deploy verification, rollback plan). Continuous improvement is driven by retrospectives that generate prioritized action items which are tracked back into the backlog.

## Docs index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## How to use

- Start here to orient to OctoAcme's project delivery approach.
- Keep the Project One‑pager and project README updated as the single source of truth.
- Propose process changes by using the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template and following the review process.

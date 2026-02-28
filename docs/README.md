# OctoAcme Project Management Docs

This docs folder contains OctoAcme's project management process documentation. These files explain how we start, plan, execute, release, and improve projects and provide a single entry point for new teammates and stakeholders.

## Purpose

- Provide a concise orientation to OctoAcme project processes
- Index the canonical process docs located in `docs/`
- Explain how to propose changes and keep process artifacts current

## Overview of project management processes

OctoAcme follows a lightweight, evidence-driven lifecycle:

1. **Initiation** — validate the problem, define success metrics, identify stakeholders, and produce a Project One-pager.
2. **Planning** — create a prioritized backlog, estimate work, define the Definition of Done, and produce a release plan.
3. **Execution** — implement in small increments with CI, PR reviews, testing, and regular demos; track progress on a project board.
4. **Release** — follow pre-release checks, deploy via automated pipelines when possible, run smoke tests, and communicate releases.
5. **Retrospective & improvement** — capture learnings, create action items, and feed improvements back into the backlog.

## Docs index

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md) — Project Management Overview
- [octoacme-project-initiation.md](octoacme-project-initiation.md) — Project Initiation Guide
- [octoacme-project-planning.md](octoacme-project-planning.md) — Project Planning
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Execution & Tracking
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — Risk Management & Communication
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release & Deployment Guide
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — Retrospective & Continuous Improvement
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Roles & Personas

## How to use these docs

- Keep project artifacts (one-pagers, risk registers, release notes) in the project repo under `docs/` or in `.copilot/` when used for Copilot Spaces context.
- Link to these canonical docs from new project READMEs and onboarding materials.

## Propose changes

- Use the provided issue template: [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) (or open a new issue and reference issue #2).
- Minor wording fixes may be proposed via PR; substantive process changes should follow the issue template and include stakeholder review.

## Maintenance guidance

- Assign an owner for each doc and review quarterly or after retrospectives that affect process.

# OctoAcme Project Management Docs

## Overview
OctoAcme uses a structured, iterative approach to project management that centers on delivering customer value quickly while keeping teams aligned and empowered. Projects begin with a lightweight initiation (a Project One‑pager) that captures the problem, measurable success criteria, stakeholders, and a high‑level timeline. Approved initiatives move into planning, where work is broken into shippable increments, acceptance criteria and a Definition of Done are defined, and risks and dependencies are captured in a Risk Register.

Execution emphasizes small, testable increments and clear ownership. Teams use a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request process that favors smaller PRs with linked issues, CI checks, and required approvals. The delivery rhythm includes daily standups, weekly delivery syncs, sprint demos, and regular PM+PdM alignment meetings to surface blockers and coordinate cross‑team work.

Quality assurance is enforced through automated CI and targeted manual checks. Unit and integration tests, linting, and security scanning run in CI; end‑to‑end smoke tests are used for critical flows before release, and manual QA is applied when acceptance criteria require it. Releases follow a checklist that includes staging verification, rollback/mitigation plans, and release notes; an incident/rollback playbook supports rapid response when needed.

Continuous improvement and communication are built into the lifecycle. Retrospectives after sprints, releases, and incidents produce prioritized action items that feed back into the backlog. Templates and escalation paths (team → PM → Product Lead → Sponsor) standardize status and incident communications, while metrics (velocity, burndown, operational dashboards) are used to monitor delivery health and inform decisions.

## Navigation — Process Documentation
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## Quick Start
- New to OctoAcme projects? Start with the [Project Management Overview](docs/octoacme-project-management-overview.md).
- Launching a new project? Follow the [Project Initiation Guide](docs/octoacme-project-initiation.md).
- Planning and scheduling work? See [Project Planning](docs/octoacme-project-planning.md).
- Day-to-day execution and QA? See [Execution & Tracking](docs/octoacme-execution-and-tracking.md) and [Risk Management & Communication](docs/octoacme-risks-and-communication.md).
- Releasing to production? Follow [Release & Deployment Guide](docs/octoacme-release-and-deployment.md).
- Closing and learning? See [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md).

## How to use and contribute
1. For new projects, follow the lifecycle from Initiation → Planning → Execution → Release → Closeout.
2. Use the relevant doc for phase‑specific guidance, templates, and checklists.
3. To propose updates, open an issue using the Process Doc Update template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
4. Keep these docs current as practices evolve; update via PRs that reference the relevant issue.

---
*Last updated: [date]. Maintained by: OctoAcme Project Management team.*

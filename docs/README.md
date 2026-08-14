# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management documentation hub. This folder contains our standardized processes and best practices for running projects successfully. Use this README as the central entry point to find guidance on initiation, planning, execution, release, and continuous improvement.

Overview

OctoAcme runs projects with a customer-first, iterative approach that emphasizes clear ownership, measurable outcomes, and psychological safety. Work starts with a lightweight initiation step (a Project One-pager capturing problem, stakeholders, success metrics, and risks), moves into planning where approved work is broken into prioritized backlog items with acceptance criteria and estimates, and proceeds through execution with small, testable increments. Releases follow a checklist-driven pipeline with pre-release verification, and every project closes with a retrospective to capture learnings and action items.

Project management at OctoAcme centers on a few key workflows: a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done); a pull request policy that prefers small PRs, includes issue links and acceptance criteria, and requires CI and at least one approval before merge; and a planning rhythm of timeboxed sprint planning, daily standups for blockers, weekly delivery syncs for status and risks, and demos at the end of sprints or milestones.

Key Artifacts & Quick Links

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

Project Lifecycle

1. Initiation — Validate the problem, align stakeholders, define success metrics (Project One-pager).
2. Planning — Break work into shippable increments, estimate, identify dependencies, and define the Definition of Done.
3. Execution — Implement, test, review, and iterate using the project board and PR workflow.
4. Release — Deploy with smoke tests, monitoring, rollback plans, and release notes.
5. Close & Retrospective — Capture learnings, create action items, and feed improvements back into the backlog.

Core Roles (At a Glance)

- Project Manager (PM): Coordinates delivery, schedules, risk tracking, and communications.
- Product Manager (PdM): Owns outcomes, prioritizes the backlog, and defines success metrics.
- Developers: Implement features, write tests, and participate in reviews and design.
- QA/Testing: Validate acceptance criteria and perform manual or automated testing where needed.
- Stakeholders: Provide inputs, approvals, and domain guidance.

How to Use These Docs

- New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand roles and lifecycle.
- Starting a new project? Complete the [Project Initiation Guide](./octoacme-project-initiation.md) and create the Project One-pager.
- In active delivery? Use [Execution & Tracking](./octoacme-execution-and-tracking.md) and the project board to manage work and escalate blockers.
- Preparing a release? Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md) checklist.
- Wrapping up? Run a retrospective and capture actions using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

Contributing & Feedback

If you want to propose changes to these process documents, open an issue using the "Add Content to Project Management Process Docs" template located at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Mention the document you want to update and include a summary and rationale.

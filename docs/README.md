# OctoAcme Project Management Docs

This folder provides OctoAcme's core project management documentation. Here you will find guides and standards for all phases of project delivery—from initiation through retrospectives and continuous improvement.

## Project Management Processes at OctoAcme

OctoAcme employs a structured, lifecycle-based approach to project management grounded in five core principles: customer-first prioritization, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

### The Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight Project One-pager with success metrics and initial timeline.
2. **Planning** — Break work into shippable increments, build a prioritized backlog with clear acceptance criteria, identify dependencies, and define the Definition of Done.
3. **Execution & Tracking** — Deliver incrementally through sprint-based iterations with daily standups, weekly syncs, automated testing, and continuous risk monitoring.
4. **Release & Deployment** — Execute controlled releases following strict pre-release checklists, with staging verification, automated deployment, and post-deploy verification.
5. **Close & Retrospective** — Capture learnings, identify actionable improvements, and track impact for future iterations.

### Key Workflows and Practices

- **Iterative Delivery**: Small, testable increments shipped frequently with pull requests ≤400 lines, automated CI/CD testing and linting, and at least one approval before merge.
- **Quality Assurance**: Unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning, and manual QA for feature acceptance.
- **Risk Management**: Continuous identification and tracking via a Risk Register, with three-level escalation paths (team-level → PM → Product Lead → Sponsor).
- **Communication Cadence**: Daily standups, weekly PM-PdM syncs, weekly delivery syncs, monthly stakeholder updates, and ad-hoc escalations as needed.
- **Metrics & Visibility**: Track velocity, burndown, success metrics, and key signals (errors, latency, usage) via dashboards and project boards.

### Core Roles

- **Project Manager** — Coordinates delivery, manages schedules, risks, and communications to ensure on-time, on-scope execution.
- **Product Manager** — Defines outcomes, prioritizes the backlog, and measures success against business and customer value metrics.
- **Developers** — Implement features, write tests, collaborate on design, and identify technical risks.
- **QA/Testing** — Validate quality and acceptance criteria.
- **Stakeholders** — Provide inputs, approvals, and business context.

---

## Documentation Index

Navigate to each document for detailed guidance on specific phases and practices:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle overview.
- **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, identify stakeholders, and decide go/no-go for planning.
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable plans, backlogs, and release timelines.
- **[Execution and Tracking](octoacme-execution-and-tracking.md)** — Day-to-day guidance on team rhythm, workflows, quality, and blocker escalation.
- **[Risks and Communication](octoacme-risks-and-communication.md)** — Manage the Risk Register, communicate status, and escalate blockers and incidents.
- **[Release and Deployment](octoacme-release-and-deployment.md)** — Standardized process for releasing features to production with rollback and incident playbooks.
- **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role definitions and responsibilities for each core persona.

---

## How to Use These Docs

- **New Team Members**: Start with [Project Management Overview](octoacme-project-management-overview.md), then read [Roles and Personas](octoacme-roles-and-personas.md) to understand your role.
- **Project Kickoff**: Use [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) to set up your project.
- **During Execution**: Reference [Execution and Tracking](octoacme-execution-and-tracking.md), [Risks and Communication](octoacme-risks-and-communication.md), and status templates for ongoing guidance.
- **Before Release**: Review [Release and Deployment](octoacme-release-and-deployment.md) checklists and playbooks.
- **After Milestones**: Use [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture and act on learnings.

---

## Contributing to These Docs

To propose updates or new content to OctoAcme's project management documentation:

1. Review the relevant process document to understand current guidance.
2. Create a GitHub Issue using the **"Add Content to Project Management Process Docs"** template (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`).
3. Propose your changes with rationale and suggested content.
4. Collaborate with the team to refine and integrate your updates.

---

## Questions or Feedback?

If you have questions about OctoAcme's project management processes or would like to suggest improvements, please open an issue or reach out to the Product Lead or Project Management team.

# OctoAcme Project Management Docs

OctoAcme runs cross-functional projects using a lightweight, phased-but-iterative lifecycle designed to deliver small, testable increments with clear ownership. Initiatives begin with a Project One‑pager (problem, objective, success metrics) and a go/no‑go decision. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, and a Definition of Done. Execution uses a project board and disciplined PR workflow to make progress predictable; releases are staged and verified with rollback plans and release notes; retrospectives capture prioritized action items that are added back into the backlog.

Workflows emphasize predictable handoffs and small change sets. Teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done and a PR workflow that links PRs to issues and acceptance criteria, runs CI (tests, linting, security scans), and requires approvals before merge. Sprint planning is timeboxed and only pulls items that meet DoD and have estimates; dependencies and risks are tracked on the board and in the Risk Register. Release types (patch/minor/major) follow a checklist that includes staging verification, smoke tests, rollback steps, and stakeholder communication.

Roles and responsibilities are explicit so everyone understands accountabilities. Product Managers define outcomes and success metrics and prioritize the roadmap; Project Managers coordinate delivery, timelines, risk registers, and stakeholder communications; Developers implement features, own tests and documentation, and participate in reviews; QA validates acceptance criteria and runs manual verification when needed; stakeholders provide input and approvals. Team cadence includes daily standups for progress/blockers, weekly PM–PdM syncs for alignment, sprint demos, and monthly stakeholder updates. Escalation paths move from team triage up to sponsor level for business‑impacting issues; security incidents follow the security runbook and on‑call notification path.

Quality and risk management are integrated across the lifecycle. Expectations include unit and integration tests, CI security scans, and end‑to‑end smoke tests for critical flows before production. The Risk Register captures ID, impact, likelihood, owner, mitigation, and status and is reviewed at weekly syncs. Teams monitor velocity, burndown, and project success metrics via dashboards to surface errors, latency, and usage. Retrospectives produce a small set of prioritized actions that are tracked back into the backlog to drive continuous improvement.

## Documents in this folder

- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

## How to use these docs

- Start with the Project One‑pager and Overview for context on any initiative.
- Keep acceptance criteria, DoD, risk register, and release notes versioned in the repo under docs/ or .copilot/ for Copilot Spaces context.
- Use the ISSUE_TEMPLATE "Add Content to Project Management Process Docs" in .github/ISSUE_TEMPLATE/ to propose updates.

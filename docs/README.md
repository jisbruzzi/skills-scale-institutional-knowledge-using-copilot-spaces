# OctoAcme Project Management Documents

This README collects the OctoAcme project management process documents and provides a short summary for each so team members can quickly find the guidance they need.

Docs included (stored in docs/):

- [Project Management Overview](./octoacme-project-management-overview.md) — high-level intro to how OctoAcme runs projects, roles, and key artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — steps and minimum deliverables to validate and authorize new projects.
- [Project Planning](./octoacme-project-planning.md) — converting an approved initiative into a plan and backlog; templates and checklists.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, QA, and reporting practices for day-to-day execution.
- [Risks & Communication](./octoacme-risks-and-communication.md) — maintaining the risk register, stakeholder communication templates, and escalation.
- [Release & Deployment](./octoacme-release-and-deployment.md) — release types, pre-release checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking improvements.
- [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities used across the process docs.

## Brief summary of OctoAcme project management processes

OctoAcme uses an iterative, customer-first approach with clear ownership and lightweight artifacts. Key elements:

- Initiation: Capture the problem, stakeholders, and measurable success metrics in a project one-pager before committing to planning.
- Planning: Convert an approved initiative into a prioritized backlog, define Definition of Done, estimate scope, and map releases/milestones.
- Execution: Deliver in short increments with small PRs, CI gates, clear acceptance criteria, and project boards to track flow (Backlog → Ready → In Progress → In Review → QA → Done).
- Release: Follow pre-release checks (tests, security scans, release notes), prefer automated pipelines, run smoke tests in staging, and perform post-deploy verifications with rollback plans prepared.
- Continuous improvement: Run retrospectives after sprints/releases/incidents, create clear action items, and track their implementation in the backlog.

## How to use

- This file is intended to live at docs/README.md as the single discoverable entry point for OctoAcme process documentation.
- Link to this README from the repository root README for visibility.
- When adding or renaming documents in docs/, update the links here.
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose edits or new process docs.

## Acceptance criteria

- Content aligns with existing process docs.
- Update improves clarity or closes a documented gap.
- (Optional) Proposed content reviewed with stakeholders as needed.

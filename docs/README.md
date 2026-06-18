# OctoAcme Project Management Docs

This folder collects OctoAcme's project management processes and templates used across Initiation, Planning, Execution, Release, and Continuous Improvement. The README provides a short summary and direct links to each detailed process document so teammates can quickly find guidance and contribute improvements.

Summary of project management processes

- Initiation: Validate ideas with a Project One-pager (problem, goal, success metrics), confirm stakeholders, and decide go/no-go for planning.
- Planning: Break approved work into a prioritized backlog, estimate, define a Definition of Done (DoD), and identify dependencies and risks.
- Execution & Tracking: Work in short iterations with daily standups, use the project board (Backlog → Ready → In Progress → In Review → QA → Done), create small PRs with linked issues and acceptance criteria, and require CI checks and reviews before merging.
- Release & Deployment: Follow pre-release checks (CI, security scans, release notes), run smoke tests in staging, deploy via automated pipelines when available, and have rollback and incident playbooks ready.
- Retrospectives & Continuous Improvement: Run regular retrospectives, capture 2–3 actionable improvements, and track them in the backlog until completed.

Core roles

- Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders.

Docs

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospectives & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

Contributing

To propose changes or add a new process document, use the "Add Content to Project Management Process Docs" issue template:

.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

---

Acceptance criteria

- Content aligns with existing process docs
- Update improves clarity or closes a documented gap
- Proposed content has been reviewed with stakeholders (if needed)

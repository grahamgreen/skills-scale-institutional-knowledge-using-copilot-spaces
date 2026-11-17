# OctoAcme Project Management Docs

The single starting point for how OctoAcme plans, delivers, and improves cross-functional projects.

## Summary of OctoAcme's project management processes

OctoAcme runs projects through a five-stage lifecycle: **initiation, planning, execution, release, and close & retrospective**. Initiation validates the business need with a project one-pager (problem, SMART goal, success metrics, stakeholders, risks) and ends at a decision gate once metrics are clear, stakeholders agree on priority, and team availability is confirmed. Planning turns the approved idea into a prioritized backlog, milestones, sprint plans, and a risk and dependency list. Execution follows a predictable team rhythm of daily standups, weekly delivery syncs, and end-of-sprint demos, with work tracked on a project board from Backlog to Done.

Every project has clear ownership. The **Project Manager** coordinates delivery, schedules, risks, and communication; the **Product Manager** owns outcomes, the roadmap, and backlog priority; **Developers** build, test, and review the work; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide input and approvals. The guiding principles are customer-first, iterative delivery in small testable increments, clear ownership, data-informed decisions, and psychological safety.

Communication is regular and escalation is explicit. The PM and Product Manager sync weekly, the delivery team holds standups, and stakeholders receive monthly (or milestone-based) updates using a standard weekly status template: progress, next steps, risks and blockers, and decisions needed. Risks live in a risk register (impact, likelihood, owner, mitigation, status) that is reviewed weekly. Blockers escalate from the team, to the PM, to the Product Lead, to the Sponsor; security incidents follow the security runbook and notify Security on-call.

Quality is built in rather than inspected at the end. Pull requests are small, link their issue and acceptance criteria, pass CI tests, linting, and security scans, and need at least one approval. Releases (patch, minor, or major) require met acceptance criteria, release notes, smoke tests, and a documented rollback plan, and they deploy to staging before production. Each sprint or project closes with a retrospective (what went well, what could improve) whose action items have owners and due dates, feeding improvements back into these docs.

## Process documents

| Document | What it covers |
| --- | --- |
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle, and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | One-pager template, initiation checklist, and the go/no-go decision gate |
| [Project Planning](octoacme-project-planning.md) | Backlog items, sprint planning, and risk and dependency management |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, board and PR workflow, quality and testing, metrics, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register and lifecycle, stakeholder updates, templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking improvement actions |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities, goals, and communication for each role |

## Proposing changes

To add or update content, open an issue with the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template, then submit a pull request that links the issue.

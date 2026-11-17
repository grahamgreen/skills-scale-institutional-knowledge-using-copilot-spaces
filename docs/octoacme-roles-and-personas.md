# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers validate that work meets its acceptance criteria and the Definition of Done before it is released. They own the test approach and give the team confidence to ship.

### Responsibilities
- Draft the initial test plan / QA approach during planning
- Review acceptance criteria for testability before work is pulled into a sprint
- Run manual QA for feature acceptance and own the QA column on the project board
- Prepare and run smoke tests in staging before release and verify after deploy
- Report defects with clear reproduction steps and severity

### Goals
- Catch defects before they reach customers
- Keep automated test coverage growing alongside new features
- Make release readiness visible and evidence-based

### Typical Communication
- Daily standups and sprint demos
- Test plans, defect reports, and PR review comments
- Release readiness sign-off to the Project Manager

---

## Project Sponsors

### Role Summary
Project Sponsors are accountable for the business outcome of a project. They authorize work, secure resources, and resolve issues the team cannot resolve on its own.

### Responsibilities
- Approve projects at the initiation decision gate
- Confirm priority and secure funding and team availability
- Act as the final escalation level (Level 3) for business-impacting blockers and risks
- Make or delegate trade-off decisions on scope, timeline, and budget

### Goals
- Ensure the project delivers measurable business value
- Remove organizational blockers quickly
- Keep the project aligned with company priorities

### Typical Communication
- Initiation review of the Project One-pager
- Monthly stakeholder updates and milestone reviews
- Escalations from the Project Manager and Product Lead

---

## Stakeholders

### Role Summary
Stakeholders are the groups affected by or contributing to a project, such as sales, support, dependent engineering teams, and customer representatives. They provide input, approvals, and feedback.

### Responsibilities
- Share requirements, constraints, and dependencies during initiation and planning
- Review and approve deliverables when their sign-off is needed
- Prepare their teams for releases (for example, support readiness)
- Give feedback on delivered increments

### Goals
- Get outcomes that meet their team's or customers' needs
- Stay informed without having to chase status
- Avoid surprises at release time

### Typical Communication
- Kickoff meeting and stakeholder alignment
- Weekly or milestone-based status updates and monthly stakeholder updates
- Release announcements and release notes

---

## Security & On-call Engineers

### Role Summary
Security and on-call engineers protect production. They respond to incidents, coordinate rollbacks, and make sure security issues follow the security incident runbook.

### Responsibilities
- Respond when incident response is triggered after a failed or harmful deployment
- Coordinate rollback to the last known-good release when necessary
- Handle security incidents per the security incident runbook
- Review security scan findings that block releases
- Capture root cause and action items for the post-incident retrospective

### Goals
- Minimize customer impact and time to recovery
- Prevent repeat incidents through follow-up actions
- Keep releases secure by default

### Typical Communication
- Incident communication: triage summary, actions, expected timeline
- On-call handoffs and incident channels
- Blameless post-incident retrospectives

---

## Role Quick Reference

"Product Lead" in other OctoAcme docs refers to the Product Manager.

| Lifecycle stage | Lead | Key contributors | Approves / escalates to |
| --- | --- | --- | --- |
| Initiation | Product Manager | Project Manager, Stakeholders | Project Sponsor |
| Planning | Project Manager | Product Manager, Developers, QA / Test Engineers | Product Manager |
| Execution | Project Manager | Developers, QA / Test Engineers | Product Manager, then Project Sponsor |
| Release | Project Manager | Developers, QA / Test Engineers, Security & On-call Engineers | Product Manager |
| Close & Retrospective | Project Manager | Whole team, Stakeholders | Project Sponsor |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


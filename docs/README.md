# OctoAcme Project Management Documentation — README

## Purpose

This README serves as the single entry point to OctoAcme's project management framework. It provides an overview of our project delivery processes, key roles, communication practices, and links to all process documentation, templates, and checklists.

## Project Management Summary

### Lifecycle

OctoAcme follows a structured project lifecycle consisting of five core phases:

1. **Initiation**: Define the problem statement, success metrics, stakeholders, and create a Project One-pager to validate business outcomes and secure approval.
2. **Planning**: Break work into shippable increments, create a prioritized backlog with acceptance criteria, identify dependencies and risks, and define the Definition of Done.
3. **Execution**: Build, test, and iterate using a visible project board workflow. Manage daily progress through standups, weekly syncs, and PR-based development with automated CI/CD.
4. **Release**: Deploy features following a prescriptive checklist with pre-release verification, smoke tests, rollout steps, rollback plans, and stakeholder communication.
5. **Retrospective**: Capture learnings, identify improvements, and convert them into actionable backlog items with clear owners and due dates.

### Board Workflow

Projects are managed using a Kanban-style board with the following columns:

- **Backlog**: Prioritized work items not yet ready for development
- **Ready**: Work items with clear acceptance criteria, ready to be picked up
- **In Progress**: Active development work
- **In Review**: Code review and PR feedback
- **QA**: Testing and validation against acceptance criteria
- **Done**: Completed, tested, and merged work

### Roles and Responsibilities

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, communications; facilitates meetings and maintains project documentation
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, measures success, and validates solutions with stakeholders
- **Developers**: Implement features, write tests, participate in reviews, and help identify technical risks
- **QA/Testing**: Validate quality, acceptance criteria, and release readiness
- **Stakeholders**: Provide inputs, approvals, and sponsorship; receive regular status updates

### Communication Cadence

- **Daily standups**: 15-minute team sync on progress, blockers, and dependencies (twice-weekly or as agreed)
- **Weekly delivery sync**: Show progress, updates, and flagged risks with PM and team
- **Weekly PM+PdM alignment**: Coordinate on priorities, decisions, and escalations
- **Monthly stakeholder updates**: Summarize progress, milestones, and upcoming work
- **Ad-hoc escalations**: As needed for critical blockers or risks

### Risk & Escalation

Risks are tracked in a **Risk Register** ([template](templates/risk-register-template.md)) with ID, description, impact, likelihood, owner, mitigation, status, and last updated date. The register is reviewed weekly during PM+PdM syncs.

**Escalation paths**:
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead for prioritization or resource decisions
- **Level 3**: Product Lead escalates to Sponsor for business-impacting issues
- **Security incidents**: Follow security incident runbook and notify Security on-call immediately

### PR & CI Quality Practices

- **Small PRs**: Keep pull requests focused and <= 400 lines when possible for faster review
- **Issue links**: Every PR must reference the related issue (e.g., "Refs #123" or "Fixes #456")
- **Acceptance criteria**: Include or reference acceptance criteria in the PR description
- **Tests required**: Add unit tests and/or integration tests for new functionality or bug fixes
- **CI gates**: All automated tests, linting, and security scans must pass before merging
- **Required approvals**: At least one approval from a team member (or as defined by team policy)
- **Security scans**: CodeQL and dependency scans run automatically; no new vulnerabilities introduced

See the full [PR & CI Checklist](checklists/pr-and-ci-checklist.md) for details.

## Docs Index

### Core Process Docs

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles, roles, lifecycle, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial validation, stakeholder alignment, and Project One-pager template
- [Project Planning](octoacme-project-planning.md) — Backlog creation, estimation, dependencies, and release planning
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Daily execution, PR workflow, quality practices, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register management, stakeholder communication, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release types, deployment checklist, rollback plans, and release notes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and tracking improvement action items
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions for PM, PdM, Developers, QA, and Stakeholders

### Checklists

- [PR & CI Checklist](checklists/pr-and-ci-checklist.md) — Pre-PR checklist for issue links, tests, CI, approvals, and security
- [Release Checklist](checklists/release-checklist.md) — Prescriptive release pipeline checklist with pre-release, deploy, post-deploy, and rollback steps

### Templates

- [Risk Register Template](templates/risk-register-template.md) — Markdown table template for tracking risks with guidance on reviews and escalation

## How to Use This README

This README is the starting point for understanding OctoAcme's project management approach. New team members should read this summary first, then explore individual documents based on their role or current project phase.

- **Project Managers**: Use this as a reference for process governance and to onboard new team members
- **Developers**: Refer to the PR & CI Checklist before opening PRs and the Execution & Tracking guide for workflow details
- **Product Managers**: Review the Planning and Initiation guides when starting new projects
- **All team members**: Consult the relevant checklist or template when performing specific activities (e.g., releases, risk management)

### Maintenance Note

Review and update this README when significant process changes are introduced. Keep the Docs Index up-to-date when adding, renaming, or removing documentation files. Link to specific docs from project repositories, release notes, and meeting agendas as the single source of truth. Consider adding project-specific customizations to your repository's `.copilot/` directory to provide Copilot Spaces with relevant context.

## Acceptance Criteria

- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

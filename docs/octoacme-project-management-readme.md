# OctoAcme Project Management Documentation

## Purpose
This README serves as the central entry point for OctoAcme's project management framework. It provides an overview of our project delivery processes, key roles, and communication practices, helping team members quickly understand how we run projects from initiation through retrospective.

## Summary

OctoAcme follows a structured project lifecycle consisting of five core phases: **Initiation** → **Planning** → **Execution** → **Release** → **Retrospective**. During initiation, teams create a Project One-pager that defines the problem statement, success metrics, stakeholders, and initial timeline. Once approved, projects move into planning where the team breaks work into shippable increments, creates a prioritized backlog with acceptance criteria, and defines the Definition of Done. The planning phase also involves identifying dependencies, estimating scope, and documenting risks in a Risk Register.

Throughout execution, teams follow a consistent workflow using a project board with columns: **Backlog → Ready → In Progress → In Review → QA → Done**. Daily standups (15 min) and weekly delivery syncs keep the team aligned, while PR-based development ensures code quality through automated CI tests, linting, security scanning, and peer reviews. Quality assurance practices include unit tests, integration tests, and end-to-end smoke tests before release. The project is guided by five key personas: **Project Manager (PM)** who coordinates delivery and manages risks, **Product Manager (PdM)** who defines outcomes and prioritizes work, **Developers** who implement features, **QA/Testing** who validate acceptance criteria, and **Stakeholders** who provide inputs and approvals.

Communication happens at multiple cadences to maintain alignment: twice-weekly standups for delivery teams, weekly PM+PdM alignment meetings, and monthly stakeholder updates. Risks are tracked in a Risk Register with clear escalation paths (Team → PM → Product Lead → Sponsor), and blocking issues are triaged during daily standups or escalated as needed. Release planning follows pre-release requirements including passing CI, security scans, drafted release notes, and documented rollback plans. After deployment, teams run post-deploy verifications and announce releases to stakeholders and support teams.

The retrospective phase closes the loop on continuous improvement. After each sprint, release, or milestone, teams hold focused retrospectives (45-75 min) to capture what went well, what could improve, and define 2-3 actionable items with clear owners and due dates. These action items are added back to the project backlog, creating a feedback loop that drives ongoing process refinement. This customer-first, iterative approach emphasizes clear ownership, data-informed decisions, and psychological safety throughout the project lifecycle.

## Docs Index

Browse the complete OctoAcme project management documentation:

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md) — Core principles, roles, lifecycle, and communication cadence
- [octoacme-project-initiation.md](octoacme-project-initiation.md) — Initial validation, stakeholder alignment, and Project One-pager template
- [octoacme-project-planning.md](octoacme-project-planning.md) — Backlog creation, estimation, dependencies, and release planning
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Daily execution, PR workflow, quality practices, and blocker escalation
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — Risk register management, stakeholder communication, and escalation paths
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release types, deployment checklist, rollback plans, and release notes
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and tracking improvement action items
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Detailed role definitions for PM, PdM, Developers, QA, and Stakeholders

## How to Use This README

This README is the starting point for understanding OctoAcme's project management approach. New team members should read this summary first, then explore individual documents based on their role or current project phase. Project Managers should ensure the docs remain up-to-date as processes evolve. Consider adding project-specific customizations to your repository's `.copilot/` directory to provide Copilot Spaces with relevant context for your project.

### Maintenance Note
Review and update this README when significant process changes are introduced. The Docs Index should always reflect the current set of available documentation files.

## Acceptance Criteria

- [x] New markdown file created at `docs/octoacme-project-management-readme.md`
- [x] README includes header and purpose statement
- [x] README contains 3-4 paragraph summary (300-450 words) covering:
  - [x] Project lifecycle: initiation → planning → execution → release → retrospective
  - [x] Core personas: PM, PdM, Developers, QA, Stakeholders
  - [x] Communication cadence: standups, weekly sync, PM+PdM alignment, monthly stakeholder updates
  - [x] Project board workflow: Backlog → Ready → In Progress → In Review → QA → Done
  - [x] PR/CI quality practices
  - [x] Risk register and escalation paths
  - [x] Retrospectives feeding action items to backlog
- [x] Docs Index section with links to all 8 documentation files
- [x] How to use this README section with maintenance note
- [x] Acceptance criteria checklist included in README

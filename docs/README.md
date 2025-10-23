# OctoAcme Project Management Docs — README

Purpose
This README provides a single entry point to OctoAcme's project management processes and links to the program process documents in this repository. Use it to find the one‑pagers, planning guidance, execution cadence, release checklists, role definitions, and continuous improvement practices used across our projects.

Project management summary
OctoAcme operates a lightweight, iterative project lifecycle that moves work from initiation → planning → execution → release → retrospective. Initiation focuses on defining the problem, success metrics, stakeholders, and a Project One‑pager to validate business outcomes. Planning turns approved initiatives into a prioritized, estimated backlog with clear acceptance criteria and a Definition of Done; dependencies and risks are identified and mapped to releases and milestones. Execution is managed via a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and short, focused pull requests that reference issues and acceptance criteria so feedback cycles remain fast. Releases follow a checklist-driven pipeline with pre-release verification, smoke tests, rollout steps, and rollback plans.

Roles and responsibilities are explicit to reduce ambiguity and speed decisions: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers (PdMs) own outcomes, prioritize the backlog, and measure success; Developers implement features, write tests, and participate in reviews; QA validates acceptance and release readiness; Stakeholders provide input, approvals, and sponsorship. These personas are assigned ownership for artifacts (one‑pager, risk register, release notes) and for action items coming out of retrospectives so improvements are tracked to completion.

Communication and quality practices are structured and repeatable. Team rhythm includes daily standups and weekly delivery syncs, weekly PM+PdM alignment, and monthly stakeholder updates. PRs are small, include issue links and acceptance criteria, and require at least one approval before merging; CI runs automated unit, integration, and security scans. Risk is tracked in a Risk Register (ID, impact, likelihood, owner, mitigation, status) and escalated through defined paths (Team → PM → Product Lead → Sponsor) with a separate runbook for security incidents. Retrospectives translate learnings into prioritized backlog action items to close the improvement loop.

Docs Index
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

How to use this README / maintenance note
- Keep this index up to date when adding, renaming, or removing docs in docs/.
- Link to specific docs from project one‑pagers, release notes, and meeting agendas as the single source of truth.
- When process changes are approved, update the relevant doc and add a short summary here.

Acceptance Criteria
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register

Use the [Risk Register Template](templates/risk-register-template.md) to track and manage project risks.

Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status
- Last updated

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths

| Level | Trigger | Escalate To | Response Time | Communication Channel |
|-------|---------|-------------|---------------|----------------------|
| Level 1: Team | Minor blockers, clarifications, day-to-day issues | Team lead or peers | Same day | Daily standup, Slack, direct message |
| Level 2: PM | Medium impact risks, cross-team dependencies, resource conflicts | Project Manager → Product Lead | 1-2 business days | Weekly sync, email, direct escalation for urgent items |
| Level 3: Executive | High impact risks affecting timeline/budget/scope, strategic decisions | Product Lead → Executive Sponsor | 2-3 business days | Email, executive briefing, escalation meeting |
| Security | Security vulnerabilities, incidents, or breaches | Security on-call (immediately) | Immediate | Security incident runbook, PagerDuty/on-call system |

**Guidelines**:
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- Escalate proactively when issues cannot be resolved at current level within response time
- Provide context, impact assessment, and proposed solutions when escalating

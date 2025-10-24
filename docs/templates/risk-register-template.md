# Risk Register Template

Use this template to track and manage project risks throughout the project lifecycle.

## Risk Register Table

| ID | Description | Impact | Likelihood | Owner | Mitigation | Status | Last Updated |
|----|-------------|--------|------------|-------|------------|--------|--------------|
| R-001 | Example: Third-party API dependency may have downtime | High | Medium | Dev Lead | Implement retry logic and circuit breaker; monitor API health | Open | 2025-01-15 |
| R-002 | | | | | | | |
| R-003 | | | | | | | |

## Field Definitions

- **ID**: Unique identifier for the risk (e.g., R-001, R-002)
- **Description**: Clear statement of the risk and potential impact on the project
- **Impact**: High, Medium, or Low - severity if the risk materializes
- **Likelihood**: High, Medium, or Low - probability the risk will occur
- **Owner**: Person responsible for monitoring and managing the risk
- **Mitigation**: Actions taken or planned to reduce impact or likelihood
- **Status**: Open, Mitigated, Closed, or Monitoring
- **Last Updated**: Date the risk entry was last reviewed or modified

## Usage Guidance

### When to Update

- **Weekly reviews**: Review and update the risk register during weekly PM+PdM sync meetings
- **During planning**: Identify and add new risks during sprint planning or milestone kickoffs
- **Ad-hoc updates**: Add or update risks immediately when new issues are identified
- **Status changes**: Update when mitigation actions are completed or risk status changes

### Escalation

When a risk requires escalation beyond the team level:

1. **Team → PM**: Developers or QA escalate to Project Manager during daily standup or via direct message
2. **PM → Product Lead**: PM escalates medium/high impact risks that require product prioritization decisions
3. **Product Lead → Sponsor**: Product Lead escalates high-impact risks affecting timeline, budget, or scope to executive sponsor
4. **Security risks**: Follow security incident runbook and notify Security on-call immediately for any security-related risks

### Risk Prioritization

Focus mitigation efforts on:
- **High Impact + High Likelihood**: Critical - immediate action required
- **High Impact + Medium/Low Likelihood**: Important - develop contingency plans
- **Medium/Low Impact + High Likelihood**: Monitor - consider preventive actions
- **Low Impact + Low Likelihood**: Track - review periodically

## Tips

- Be specific in risk descriptions - avoid vague statements
- Assign a single owner per risk for clear accountability
- Update mitigation plans with concrete, actionable steps
- Close risks promptly when they no longer apply
- Review closed risks in retrospectives to capture learnings

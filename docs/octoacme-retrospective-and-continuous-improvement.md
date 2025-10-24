# OctoAcme — Retrospective & Continuous Improvement

## Purpose
Capture learnings and convert them into actionable improvements.

## When
After each sprint, release, or important milestone. Also after incidents.

## Structure
- What went well
- What could be improved
- Action items (owner, due date)
- Follow-up on previous action items

## Running a Retrospective
- Timebox: 45–75 minutes depending on team size
- Use an anonymous idea board if needed to encourage candor
- Prioritize 2–3 top action items to avoid overload

## Tracking Improvements
- Add action items to the project backlog or issues with clear owners and timelines
- Review outstanding actions in the weekly PM sync

## Tracking Retrospective Action Items

To ensure retrospective insights drive real improvements, follow this process:

1. **Create issues for action items**: After each retrospective, create GitHub issues for each prioritized action item
2. **Label appropriately**: Apply the `retro-action` label to distinguish retrospective improvements from feature work
3. **Assign owners**: Assign a specific owner to each issue who is accountable for driving it to completion
4. **Set due dates**: Add a target completion date or milestone to maintain momentum
5. **Link back to retros**: Include a link or reference to the retrospective notes/document in the issue description for context
6. **Track in project board**: Add retrospective action items to the project board so they're visible alongside other work
7. **Review progress**: Review retrospective action items during weekly PM+PdM sync meetings to track progress and unblock issues
8. **Close the loop**: When an action item is completed, update the retrospective document to mark it as done and capture the outcome

**Example issue template**:
```
Title: [Retro Action] Improve test coverage for API endpoints

Description:
From Sprint 5 Retrospective (link to retro doc)

Action item: Increase unit test coverage for API endpoints from 60% to 80%

Success criteria:
- [ ] Coverage report shows >= 80% for api/ directory
- [ ] All new endpoints have tests
- [ ] CI fails if coverage drops below threshold

Owner: @developer-name
Due: End of next sprint
Label: retro-action
```

This structured approach ensures retrospective insights translate into concrete improvements rather than being forgotten.

## Example Action Item Template
- Title:
- Description:
- Owner:
- Due date:
- Success criteria:

## Continuous Improvement Culture
- Measure impact of action items
- Celebrate improvements and make small, iterative changes

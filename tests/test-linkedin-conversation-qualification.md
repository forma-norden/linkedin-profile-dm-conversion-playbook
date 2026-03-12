# Test: linkedin-conversation-qualification

Load skill: `.claude/skills/linkedin-conversation-qualification.md`

## Prompt

```text
Read .claude/skills/linkedin-conversation-qualification.md

Inputs:
- DM thread: prospect asked about pricing and implementation speed
- segment target: RevOps and VP Sales
- qualification thresholds:
  - role fit >= 4/5
  - urgency >= 3/5
  - use-case fit >= 4/5

Return scorecard, route decision, transition message, and handoff fields.
```

## Must Pass Checklist

- [ ] Produces explicit scorecard by dimension
- [ ] Chooses route with rationale
- [ ] Generates transition message
- [ ] Includes handoff fields
- [ ] Includes follow-up due date

## Failure Indicators

- route chosen without score evidence
- no disqualify path handling
- no handoff schema


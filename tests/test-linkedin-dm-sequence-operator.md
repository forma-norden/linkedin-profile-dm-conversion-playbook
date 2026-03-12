# Test: linkedin-dm-sequence-operator

Load skill: `.claude/skills/linkedin-dm-sequence-operator.md`

## Prompt

```text
Read .claude/skills/linkedin-dm-sequence-operator.md

Inputs:
- trigger: profile visit + new connection
- segment: VP Sales, 100-500 employee SaaS
- objective: qualify for workflow teardown call
- max follow-ups: 4

Return a full DM sequence with objective per message and close policy.
```

## Must Pass Checklist

- [ ] Uses trigger-specific opener
- [ ] Adds net-new value in follow-ups
- [ ] Keeps single objective per message
- [ ] Includes intent checks before meeting ask
- [ ] Includes close or revisit policy

## Failure Indicators

- bump-only follow-up messages
- meeting ask without qualification step
- no close logic


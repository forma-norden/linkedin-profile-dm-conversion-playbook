# Test: linkedin-pipeline-governance

Load skill: `.claude/skills/linkedin-pipeline-governance.md`

## Prompt

```text
Read .claude/skills/linkedin-pipeline-governance.md

Inputs:
- campaign artifacts: profile copy, lead magnet post, DM sequence
- team: 1 content lead, 1 operator, 1 closer
- SLA: first response within 24h
- metrics: acceptance rate, response rate, qualification rate

Return control checklist result, launch decision, and weekly review plan.
```

## Must Pass Checklist

- [ ] Runs quality and safety checks across all artifacts
- [ ] Flags blocked launch items
- [ ] Includes required fixes for failures
- [ ] Provides explicit launch decision
- [ ] Defines weekly optimization review plan

## Failure Indicators

- launch approved despite failed high-risk controls
- no owner for SLA-critical steps
- no metrics baseline


# Test: linkedin-post-type-composer

Load skill: `.claude/skills/linkedin-post-type-composer.md`

## Prompt

```text
Read .claude/skills/linkedin-post-type-composer.md

Inputs:
- bucket: proof and results
- post type: case study
- core claim: booked 14 qualified calls in 21 days
- CTA objective: conversation

Return 3 hooks, full post draft, CTA rationale, and quality check result.
```

## Must Pass Checklist

- [ ] Generates 3 hook options
- [ ] Uses case-study structure
- [ ] Includes evidence block for claim
- [ ] Uses CTA aligned to conversation objective
- [ ] Includes quality check output

## Failure Indicators

- post structure does not match selected type
- claim has no evidence reference
- no CTA rationale


# Test: linkedin-icp-and-positioning

Load skill: `.claude/skills/linkedin-icp-and-positioning.md`

## Prompt

```text
Read .claude/skills/linkedin-icp-and-positioning.md

Inputs:
- offer: signal-based outbound workflow build
- ACV: 25k
- ICP: B2B SaaS, 50-400 employees, US/UK
- roles: VP Sales, RevOps Lead, Founder
- triggers: hiring SDRs, high LinkedIn engagement, recent funding

Return segment table, positioning statements, and disqualification rules.
```

## Must Pass Checklist

- [ ] Creates multi-segment output by role and trigger
- [ ] Defines pain and proof by segment
- [ ] Includes explicit disqualification rules
- [ ] Includes positioning statements for profile and DM use
- [ ] Keeps output operational, not generic

## Failure Indicators

- one undifferentiated segment
- no proof mapping
- no disqualification logic


# Test: linkedin-profile-conversion-architecture

Load skill: `.claude/skills/linkedin-profile-conversion-architecture.md`

## Prompt

```text
Read .claude/skills/linkedin-profile-conversion-architecture.md

Inputs:
- segment: RevOps leader at Series A/B SaaS
- offer: CRM and routing workflow redesign
- proof assets: two case snapshots and one teardown guide
- CTA destination: DM keyword "ROUTE"

Return headline options, about section, featured plan, and CTA placement map.
```

## Must Pass Checklist

- [ ] Produces multiple headline options
- [ ] Includes about section with proof and CTA
- [ ] Defines featured section by intent stage
- [ ] Includes CTA hierarchy and placement map
- [ ] Includes profile audit score or checklist

## Failure Indicators

- no proof section in about copy
- CTA lacks route or destination
- no audit output


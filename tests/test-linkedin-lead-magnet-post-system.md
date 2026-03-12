# Test: linkedin-lead-magnet-post-system

Load skill: `.claude/skills/linkedin-lead-magnet-post-system.md`

## Prompt

```text
Read .claude/skills/linkedin-lead-magnet-post-system.md

Inputs:
- segment: founders and VP Sales in B2B SaaS
- lead magnet: "Signal Routing Blueprint"
- objective: qualify comment leads into DM conversations
- response SLA: 24 hours

Return post draft, response tree, qualification prompts, and tracking schema.
```

## Must Pass Checklist

- [ ] Includes hook, value, and single CTA action
- [ ] Defines connected and non-connected response branches
- [ ] Includes qualification prompt before meeting ask
- [ ] Defines ownership and response SLA
- [ ] Defines tracking fields

## Failure Indicators

- no branch logic by connection status
- multiple CTA asks in post
- no tracking schema


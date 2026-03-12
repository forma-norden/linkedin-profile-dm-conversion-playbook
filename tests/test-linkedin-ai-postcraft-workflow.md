# Test: linkedin-ai-postcraft-workflow

Load skill: `.claude/skills/linkedin-ai-postcraft-workflow.md`

## Prompt

```text
Read .claude/skills/linkedin-ai-postcraft-workflow.md

Inputs:
- objective: authority post
- segment: B2B SaaS founder, 50-300 employees
- proof assets: two verified client outcomes
- brand bans: no hype claims, no fake urgency

Return prompt payload, 3 drafts, claim verification log, and final selected draft.
```

## Must Pass Checklist

- [ ] Builds a structured prompt payload
- [ ] Produces 3 distinct drafts
- [ ] Includes claim verification log
- [ ] Selects one final draft with notes
- [ ] Avoids unverified claims

## Failure Indicators

- no verification log
- drafts contain fabricated metrics
- no final selection rationale


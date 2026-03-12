# Test: linkedin-content-bucket-planner

Load skill: `.claude/skills/linkedin-content-bucket-planner.md`

## Prompt

```text
Read .claude/skills/linkedin-content-bucket-planner.md

Inputs:
- weekly objective: 20 qualified DM conversations
- offer priority: signal-based outbound setup
- publish capacity: 5 posts
- available proof assets: 3 case snapshots

Return weekly bucket allocation and post plan with fallback queue.
```

## Must Pass Checklist

- [ ] Allocates posts across all three buckets
- [ ] Ties post plan to objective
- [ ] Maps proof assets to proof-heavy posts
- [ ] Includes fallback queue
- [ ] Keeps one objective per post

## Failure Indicators

- no bucket allocation logic
- missing proof map
- no fallback plan


---
name: linkedin-profile-dm-conversion-playbook
description: Expert LinkedIn organic growth and DM pipeline consultant for B2B. Use when the user asks about LinkedIn profiles, DM sequences, LinkedIn content, LinkedIn posts, connection requests, lead magnets, LinkedIn engagement, content strategy, authority positioning, or converting LinkedIn activity into pipeline. Also triggers on "LinkedIn profile", "DM", "direct message", "LinkedIn content", "post", "connection request", "lead magnet", "LinkedIn strategy", "authority", "LinkedIn growth", "LinkedIn followers". Do NOT use for LinkedIn Ads (use linkedin-ads-campaign-playbook or linkedin-claude-code-workflow), email copy (use cold-email-copy-playbook), or Clay enrichment (use clay-claude-code-skill-pack).
---

## Setup (Run Once Per Session)

Before loading any skill or resource, locate this skill's install directory:
1. Search for `**/linkedin-profile-dm-conversion-playbook/**/SKILL.md`
2. The directory containing this SKILL.md is `SKILL_BASE`
3. Skills are at: `{SKILL_BASE}/[skill-name].md`

Always resolve SKILL_BASE dynamically. Never assume a hardcoded install location.

# LinkedIn Organic Growth and DM Pipeline Expert, Orchestrator

You are an expert LinkedIn strategist who builds conversion-focused profiles, content systems, and DM pipelines for B2B operators.

## Skill Routing

| User Intent | Skill | Trigger Phrases | Load |
|-------------|-------|-----------------|------|
| ICP targeting and positioning | **icp-positioning** | "ICP", "target audience", "positioning", "who to target" | Read `{SKILL_BASE}/linkedin-icp-and-positioning.md` |
| Profile optimization | **profile-architecture** | "profile", "headline", "about section", "banner", "optimize profile" | Read `{SKILL_BASE}/linkedin-profile-conversion-architecture.md` |
| Lead magnet posts | **lead-magnet** | "lead magnet", "comment to DM", "resource post", "gated content" | Read `{SKILL_BASE}/linkedin-lead-magnet-post-system.md` |
| DM sequences | **dm-sequence** | "DM", "direct message", "DM sequence", "message template", "outreach DM" | Read `{SKILL_BASE}/linkedin-dm-sequence-operator.md` |
| Conversation qualification | **conversation-qual** | "qualify", "DM conversation", "pipeline", "move to call" | Read `{SKILL_BASE}/linkedin-conversation-qualification.md` |
| Pipeline governance | **pipeline-governance** | "pipeline", "governance", "quality", "SLA", "measurement" | Read `{SKILL_BASE}/linkedin-pipeline-governance.md` |
| AI-assisted post drafts | **ai-postcraft** | "AI post", "write post", "draft post", "Claude post" | Read `{SKILL_BASE}/linkedin-ai-postcraft-workflow.md` |
| Content planning | **content-planner** | "content plan", "content calendar", "topics", "pillars", "what to post" | Read `{SKILL_BASE}/linkedin-content-bucket-planner.md` |
| Post composition | **post-composer** | "write", "format", "post type", "carousel", "list post", "story post" | Read `{SKILL_BASE}/linkedin-post-type-composer.md` |
| Distribution and engagement | **distribution** | "distribution", "engagement", "commenting", "share", "reach" | Read `{SKILL_BASE}/linkedin-distribution-loop-operator.md` |
| Team operations | **team-ops** | "team", "SLA", "workflow", "who does what", "content team" | Read `{SKILL_BASE}/linkedin-content-team-ops.md` |
| Authority positioning | **authority-flywheel** | "authority", "thought leadership", "flywheel", "brand building" | Read `{SKILL_BASE}/linkedin-authority-channel-flywheel.md` |

## Decision Flow

```
User Request
├─ Building/optimizing my profile? ────────> profile-architecture
├─ Who should I target? ───────────────────> icp-positioning
├─ What content should I post? ────────────> content-planner
├─ Write a specific post? ─────────────────> post-composer or ai-postcraft
├─ How to get more reach? ─────────────────> distribution
├─ Setting up lead magnet posts? ──────────> lead-magnet
├─ Writing DM sequences? ─────────────────> dm-sequence
├─ How to qualify DM conversations? ───────> conversation-qual
├─ Managing a content team? ───────────────> team-ops
├─ Building authority/thought leadership? ─> authority-flywheel
└─ Full LinkedIn system build?
    └─ Chain: icp-positioning > profile-architecture > content-planner > post-composer > lead-magnet > dm-sequence > conversation-qual
```

## Key Benchmarks

| Metric | Value |
|--------|-------|
| Hook length | First 210 characters (before "see more") |
| Carousel reach multiplier | 2.5-3.5x vs text posts |
| Golden Hour engagement window | First 60-90 min (80%+ of reach) |
| Connection acceptance (cold) | 15-25% |
| Connection acceptance (warm) | 40-60% |
| DM reply rate (cold) | 5-10% |
| DM reply rate (warm engagement) | 25-40% |
| Posting frequency | 3-4x per week for growth |
| Best posting times | Tue-Thu, 7:30-8:30 AM |
| Comment weight (15+ words) | 4x vs likes |

## Universal Principles

1. **Profile converts, content attracts.** Fix your profile before scaling content.
2. **Golden Hour determines reach.** Engage within 60 min of posting.
3. **DMs follow engagement.** Never cold DM without prior touchpoint.
4. **One post, one idea.** Multi-topic posts underperform.
5. **Carousels for reach, text for depth.** Format selection drives distribution.
6. **Links kill reach.** External links reduce distribution by 40-60%. Put links in comments.

# Ecosystem: linkedin-profile-dm-conversion-playbook

How this repo connects to the rest of the Forma Norden GTM library.

## Works With

| Repo | Relationship | When to use together |
|------|-------------|---------------------|
| `linkedin-claude-code-workflow` | Parallel | This repo handles organic and DM, that repo handles ads and signal processing |
| `cold-email-copy-playbook` | Parallel | Multi-channel: email copy here, LinkedIn messaging there |
| `signal-based-list-building-workflow` | Upstream | LinkedIn engagement signals feed list building |
| `buying-window-signal-workflow` | Upstream | Signal scoring determines DM timing and approach |

## Suggested Skill Chains

1. Content to pipeline: content-bucket-planner > post-type-composer > lead-magnet > dm-sequence > conversation-qualification > pipeline-governance

# linkedin-ai-postcraft-workflow

Use this skill to create high-quality LinkedIn post drafts with AI while
preserving brand voice, proof integrity, and operator control.

## Required Inputs

- brand voice rules and banned phrases
- ICP language and pain map
- source evidence (case studies, metrics, screenshots)
- post objective (authority, conversation, lead magnet)

## Workflow Rules

- AI produces draft, human owns final publication
- no unverified claims in final copy
- keep line-level readability and implementation clarity
- one post objective per draft

## Execution Sequence

1. Load context pack:
   - brand guide
   - ICP document
   - proof library
   - best-performing reference posts
2. Build structured prompt with:
   - hook constraints
   - post type
   - tone constraints
   - CTA type
3. Generate 3 draft variants.
4. Run fact and claim check against source evidence.
5. Run final human edit pass before publishing.

## Output Contract

Return:

- prompt_payload
- draft_variants (3)
- claim_verification_log
- final_post_version
- publish_notes

## Failure Conditions

- draft contains unverified stats
- writing style ignores brand constraints
- no claim verification log provided


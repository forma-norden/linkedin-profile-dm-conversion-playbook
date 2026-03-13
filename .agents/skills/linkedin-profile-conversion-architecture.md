# linkedin-profile-conversion-architecture

Use this skill to structure LinkedIn profiles for conversion from visit to DM.

## Required Inputs

- segment table from `linkedin-icp-and-positioning`
- offer statement
- proof assets and case references
- call-to-action destination

## Profile Layers

1. Headline:
   - role and ICP relevance
   - clear outcome plus mechanism
2. About:
   - pattern interrupt
   - credibility and pain articulation
   - proof and CTA
3. Featured:
   - one proof asset
   - one practical resource
   - one conversion CTA asset
4. CTA placement:
   - banner
   - about section
   - featured section
   - custom button

## Execution Sequence

1. Generate two headline options per priority segment.
2. Draft one modular about section with segment-specific variants.
3. Build featured-section asset stack by buyer intent stage.
4. Define CTA hierarchy (low friction first, call ask later).
5. Run profile audit checklist and list revision actions.

## Output Contract

Return:

- headline_options
- about_section_template
- featured_section_plan
- cta_placement_map
- profile_audit_score

## Failure Conditions

- headline without outcome clarity
- about section with no proof block
- CTA placement without intent-stage logic


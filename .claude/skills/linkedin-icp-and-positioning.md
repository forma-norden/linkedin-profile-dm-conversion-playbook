# linkedin-icp-and-positioning

Use this skill to define target segments and positioning language for LinkedIn
profile and DM execution.

## Required Inputs

- offer and ACV range
- target industries and geographies
- target roles and buying committee map
- known trigger signals
- available proof assets

## Execution Sequence

1. Build core ICP definition:
   - company size band
   - role priorities
   - problem urgency signals
2. Create segment rows by role and trigger:
   - inbound content engager
   - profile visitor
   - outbound target via search or list
3. For each segment define:
   - primary pain and desired outcome
   - language style
   - acceptable proof format
4. Set disqualification rules:
   - no clear role ownership
   - weak problem-match evidence
   - out-of-scope geography or market
5. Produce positioning statements for profile and DM use.

## Output Contract

Return:

- segment_table
- positioning_statement_by_segment
- do_not_target_rules
- proof_requirements

## Failure Conditions

- one generic positioning for all segments
- no disqualification criteria
- no traceable proof mapping


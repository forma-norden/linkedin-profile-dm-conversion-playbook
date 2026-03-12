# linkedin-content-bucket-planner

Use this skill to plan weekly content using conversion-oriented buckets.

## Required Inputs

- weekly business objective
- offer priorities
- audience segment priorities
- available proof assets
- publishing capacity

## Core Buckets

1. proof and results
2. education
3. identity and beliefs

## Execution Sequence

1. Assign weekly goals:
   - credibility goal
   - conversation goal
   - conversion goal
2. Allocate post volume per bucket based on goal mix.
3. Map each planned post to one offer or one conversation outcome.
4. Tag required proof assets for each post slot.
5. Build weekly plan with fallback ideas.

## Output Contract

Return:

- weekly_bucket_allocation
- post_plan_table
- proof_dependency_map
- fallback_queue

## Failure Conditions

- bucket plan not tied to business objective
- proof-heavy posts without proof source
- no fallback queue for missed publish windows


# linkedin-pipeline-governance

Use this skill to enforce quality and operational controls across profile, post,
and DM workflows.

## Required Inputs

- campaign plan and message assets
- team roles and ownership
- response SLAs
- measurement plan

## Governance Controls

1. Message quality:
   - no fabricated personalization
   - no unverifiable claim blocks
2. Operational quality:
   - owner assigned for every response path
   - response SLA by trigger type
3. Safety and compliance:
   - suppression handling
   - respectful frequency limits
4. Measurement:
   - connection acceptance rate
   - response rate by trigger
   - qualification rate
   - routed-to-meeting rate

## Execution Sequence

1. Run prelaunch checklist for all workflow artifacts.
2. Flag failed controls and required corrections.
3. Approve or block launch.
4. Define weekly review and optimization loop.

## Output Contract

Return:

- control_checklist_result
- blocked_items
- required_fixes
- launch_decision
- weekly_review_plan

## Failure Conditions

- launch approved with failed high-risk controls
- no owner for SLA-critical step
- no measurement baseline


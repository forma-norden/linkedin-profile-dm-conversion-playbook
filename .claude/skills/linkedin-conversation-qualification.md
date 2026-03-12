# linkedin-conversation-qualification

Use this skill to qualify DM conversations and route to the correct next step.

## Required Inputs

- active DM thread context
- segment and ICP criteria
- qualification thresholds
- routing destinations (resource, audit, meeting, nurture)

## Qualification Dimensions

- role fit
- problem urgency
- use-case relevance
- timing and ownership

## Execution Sequence

1. Extract key signals from conversation thread.
2. Score qualification dimensions with explicit thresholds.
3. Assign route:
   - resource path
   - diagnostic call path
   - nurture path
   - disqualify path
4. Generate transition message for selected route.
5. Log handoff fields for CRM or tracker.

## Output Contract

Return:

- qualification_scorecard
- chosen_route
- transition_message
- handoff_fields
- follow_up_due_date

## Failure Conditions

- route assigned without score explanation
- no disqualify path
- no handoff schema for next owner


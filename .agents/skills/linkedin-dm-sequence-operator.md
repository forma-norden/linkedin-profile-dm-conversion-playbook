# linkedin-dm-sequence-operator

Use this skill to run DM workflows for warm and semi-warm LinkedIn triggers.

## Required Inputs

- trigger type (profile visit, commenter, follower, list target)
- segment definition
- opening objective (qualify, deliver resource, or route to call)
- max follow-up count

## Sequence Policy

- each message has one objective
- each follow-up adds net-new value
- no pressure or manipulative framing
- meeting ask only after relevance or intent confirmation

## Execution Sequence

1. Select opener variant by trigger.
2. Draft message 1 with context plus low-friction question.
3. Define message 2:
   - value add
   - proof or insight
4. Define message 3+:
   - qualification prompt
   - routing or close logic
5. Set no-response close and revisit window.

## Output Contract

Return:

- message_sequence_1_to_n
- objective_per_message
- intent_signal_checks
- close_or_revisit_policy

## Failure Conditions

- generic opener without trigger reference
- repeated bump-style follow-ups
- meeting ask before any qualification signal


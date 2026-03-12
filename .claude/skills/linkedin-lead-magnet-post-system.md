# linkedin-lead-magnet-post-system

Use this skill to design and operationalize lead-magnet posts for qualified
conversation capture.

## Required Inputs

- offer and target segment
- lead magnet asset
- post objective (conversation, qualification, or meeting)
- response capacity and SLA

## Post Design Rules

- one clear value promise
- one primary CTA action
- low-friction comment trigger
- explicit response path for connected and non-connected users

## Execution Sequence

1. Draft post using four blocks:
   - hook
   - value proposition
   - action instruction
   - optional bonus incentive
2. Define response tree:
   - connected commenter response
   - non-connected commenter response
   - follow-up branch by intent signal
3. Set timing policy and response SLA.
4. Add qualification question branch before meeting ask.
5. Define tracking fields for each responder.

## Output Contract

Return:

- post_copy_draft
- comment_response_tree
- qualification_prompts
- response_SLA_and_owner
- tracking_schema

## Failure Conditions

- multiple competing CTA actions
- no branch for unconnected commenters
- no qualification step before call ask


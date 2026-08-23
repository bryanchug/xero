# Merge, plans, and Done

## Imperative vs open

| Ask | What to do |
| --- | --- |
| **Imperative** (“Please delete/add/build…”, “ship it”, “merge this”) | Execute. Open the PR ready. Merge when repo policy allows. Invite review after. |
| **Open** (“let’s build together”, “I need your help”) | Read the plan back. Invite him to shape it. Leave merge to Bryan. |
| **Ambiguous** | Default to open / collaborate. |

Assigned to Kessler SA **and** In Progress is a go for that ticket (skip
plans-first wait).

## Done (comms)

When saying Done, say whether Bryan still needs to merge a PR.

- PR open / waiting → **Bryan still needs to merge**
- Already merged / no PR → **already merged** / **nothing to merge**
- Jira ticket finish ≠ Jira Done — For Review + reassign to Bryan

## Neon exception

Just-additive neon (+ pin-only bump) → merge yourself.

## Cloud / this Cursor setup

Some Cloud Agent runs forbid the agent from merging PRs. If merge is blocked,
say clearly that **Bryan still needs to merge**.

## Live rules

- `imperative-vs-open.mdc`
- `neon-additive-merge.mdc`
- `slack-reply-habits.mdc` (Done clause)
- `jira-for-review-handoff.mdc`

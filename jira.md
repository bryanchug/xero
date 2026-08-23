# Jira — secretary habits

Site: [r1sen.atlassian.net](https://r1sen.atlassian.net) · Cloud ID
`62991758-1c06-41ad-b049-3386f489781d`.

**Default transport:** `REI_ATLASSIAN_TOKEN` via
`https://api.atlassian.com/ex/jira/{cloudId}/…`. Atlassian MCP is fallback
only (never for comments). Token authorship is still the Kessler SA until
Bryan cuts a new user.

## Hard gates

- **Do not start** a ticket until assignee is the Kessler SA
  (`712020:8bef2599-ec62-429c-9855-3a0e88209dc2`) **and** status is
  **In Progress**. Explicit pickup ask from Bryan → self-assign + flip
  In Progress, then start.
- **Finish** → reassign to Bryan (`5a6acefc7cb92a26e55c1eeb`) and
  **For Review**. Never mark **Done** unless Bryan asks.

## On create

- Folder → project map: `jira-project-folders.mdc` (longest prefix)
- Client locks first (e.g. Fat Butcher / TFB → `RISEN`, not `RSA`)
- Apply a fitting open epic (Parent / Epic Link); if none, recommend one
  (buy requests: create an epic if none)
- Put the ticket on the project’s **active sprint**
- Clickable Slack thread permalink in the description
- Pertinent artifact URLs go on the issue **and** in Slack the same turn

## Relocate

**Move / bulk change.** Do not clone + Done the old tickets.

## Live rules

- `jira-project-folders.mdc`
- `client-jira-project-locks.mdc`
- `jira-epic-on-create.mdc`
- `jira-active-sprint-on-create.mdc`
- `jira-assigned-in-progress-work.mdc`
- `jira-for-review-handoff.mdc`
- `jira-sa-token-default.mdc`
- `jira-slack-thread-link.mdc`
- `jira-move-not-clone.mdc`
- `buy-request-ticket.mdc`
- `pertinent-links-jira-and-slack.mdc`
- `zero-avatars-atlassian.mdc`

File Xero work under `xero/` → primary `BRY`.
Jira project key `REI` may still exist on the site — file there only if Bryan
names that project.

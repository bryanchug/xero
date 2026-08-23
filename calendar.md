# Calendar — secretary habits

Timezone default: **Asia/Manila**.

## Lookup

When asked when / where / what about a scheduled event: check
**`BCC - Bryan Carl Chug`** first (`calendarId` `bryan.chug@r1sen.one`)
via `REI_GCP_CREDENTIALS_CONFIG`. Then other calendars. Then Slack / neon /
Jira / Drive.

Household **Ching** (Hannaiah Saulog) ≠ **Mr Ching**.

## Note (Bryan tells an upcoming event)

1. Parse title, who, date/time, place.
2. **Always set `location`** (venue, known school default, TBA, or ask once).
3. Conflict-check BCC first (`events.list`).
4. **Always add** to BCC even on hard overlap — flag the conflict clearly.
5. Do **not** create neon journal files dated in the future.

## Invites the agent proposes

If Bryan did not name a time: **1:00pm–6:00pm Asia/Manila** (start ≥ 13:00,
end ≤ 18:00). Honor times he already gave. Always set `location`.

## Live rules

- `event-lookup-bcc-calendar-first.mdc`
- `event-note-bcc-calendar-conflict-check.mdc`
- `calendar-invite-availability-window.mdc`
- `rei-gcp-credentials-default.mdc` (env name unchanged; see [gcp.md](gcp.md))

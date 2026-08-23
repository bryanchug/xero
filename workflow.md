# Workflow

> Work is data and data is work. There should be no barrier.

```text
Slack  →  Cursor env  →  repo  +  MCPs
```

| Stage | Role |
| --- | --- |
| **Slack** | Where work starts. Tag `@Cursor`; the thread is source of truth. |
| **Cursor env** | Cloud Agent or local Cursor with full tool access. |
| **Repo** | Durable record in `bryanchug/bryanverse` and its grafts. |
| **MCPs** | Jira, Confluence, Google, Slack, GitHub — without leaving the thread. |

## In practice

1. Start in Slack.
2. Sync wall clock on Cloud / automation wakes **before** Slack ack or Google.
3. Short Slack ack (tag Bryan), then a short strategy beat, then do the work.
4. Land changes in git. Dual-post pertinent URLs to Slack **and** Jira.
5. Follow [merge-and-plans.md](merge-and-plans.md) for merge ownership.
6. Ticket work: assigned to the Kessler SA + In Progress before starting;
   hand off with For Review + reassign to Bryan. Never mark Jira **Done**
   unless Bryan asks.

Default persona is **Xero Zhuang** ([personality.md](personality.md)).
Live rule pointers: [rules-index.md](rules-index.md).

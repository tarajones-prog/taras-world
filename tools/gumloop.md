# Gumloop — AI Automation Platform

**What:** Gumloop is an AI automation platform used by the Opendoor Agent Partnerships team to build and run workflow automations.

---

## Current Status

- **Cohort completed:** Feb 13, 2026 (5-day cohort, Days 1, 3, 5)
- **Automations live:** None yet — cohort was training; implementation is the next phase
- **Key insight from cohort:** Automation works best for repetitive notification flows — weekly updates, welcome emails, payment triggers

---

## Automation Ideas Backlog

These are potential automations identified during the Gumloop cohort. Prioritized roughly by expected impact:

| Automation | Description | Priority |
|-----------|-------------|----------|
| Weekly HSA Updates Bot | Sends HSAs all Cash/CP/acquisition CITY tooling updates; re-sends if not acknowledged | High |
| New Agent Welcome | Weekly pull of first-time Opendoor offer requesters → auto-send welcome email from PSMteam@ | High |
| ALO Payment Automation | Auto-pull closing info, calculate payment amount, send email to agent before Ramp PO | Medium |
| Agent Bonus Points Trigger | When agent hits 400 points → auto-email about $5,000 bonus opportunity at next closing | Medium |
| Emoji-to-List Workflow | When a Slack message is emoji-reacted, add it to a list with context | Low |

---

## What Gumloop Is Good For

Based on cohort learnings:
- **Repetitive notification flows** — same message, different data, sent on a schedule
- **Trigger-based emails** — when X happens → send Y
- **Data pulls + summaries** — pull from a sheet, summarize, send
- **Cross-tool automations** — connect Google Drive, Slack, Gmail, etc.

Not ideal for:
- Complex decision trees requiring human judgment
- One-off tasks that don't repeat
- Anything requiring real-time data from locked internal systems (CITY, Linear)

---

## Relationship to Superdojo

Gumloop and [Superdojo](../integrations/superdojo.md) (Mike Billet's tool) may serve complementary use cases:
- **Gumloop** — external automation platform, API-driven, good for notification and data flows
- **Superdojo** — internal AI-assisted tool, likely deeper CITY/Linear integration

Both are worth exploring — they likely don't compete.

---

## Next Steps

- [ ] Prioritize first automation to build (recommendation: Weekly HSA Updates Bot or New Agent Welcome)
- [ ] Get Mark Biggins alignment on which automation to start with
- [ ] Connect with Gumloop support for any implementation questions
- [ ] Apply cohort learnings before they go stale

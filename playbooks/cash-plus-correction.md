# Playbook: Cash Plus CITY Correction

**Trigger:** A property is showing the wrong product type (Cash vs. Cash Plus) in CITY or Town.

---

## Step 1 — Verify the Correct Product Type
Check what the property **should** be:
- Review executed contract / buyer docs
- Check seller's stated intent at offer acceptance
- Check original offer parameters in CITY

Do not make any correction until you can verify. An incorrect correction is worse than the original error.

## Step 2 — Check for Outliers
Before adding to the correction sheet, flag if:
- Customer wanted a different list price than what's in the contract
- There's a commission calculation that depends on product type
- Multiple related transactions are affected

Outliers need separate requests — they can't be batch-corrected.

## Step 3 — Add to the Correction Sheet
Open the CITY correction sheet (shared with engineering team, Google Drive).

Add a row:

| Column | What to Enter |
|--------|--------------|
| Address | Full property address |
| Token / TXN ID | CITY transaction token |
| Current State | What CITY shows now |
| Correct State | What it should be |
| Reason | Brief explanation |
| Outlier? | Yes/No — flag separately if Yes |

**Review the full sheet before sending — not just spot-checks.** (Lesson learned.)

## Step 4 — Confirm with Engineering
- Share updated sheet with engineering contact via Slack
- Confirm correction is queued
- Get confirmation before marking resolved

## Step 5 — Linear Ticket (if needed)
If this requires a code fix:
- Create/update a Linear ticket in the **Sales & Transactions** team
- Include: description, affected transactions, priority
- Link correction sheet in the ticket

## Step 6 — Flag Systematic Bugs
If multiple properties are affected by the same root cause:
- Flag to Mark Biggins for retro or follow-up
- Don't wait for engineering to notice on their own

---

## Escalation

See [../programs/cash-plus/escalation-guide.md](../programs/cash-plus/escalation-guide.md)

---

## Key Lessons

> Review the **full** correction sheet before sending, not just spot-checks. A batch bug affecting many properties was caught late because of incomplete review.

> Always advocate for a named DRI on CP bugs and corrections — "no one knows who to go to" is a solvable problem.

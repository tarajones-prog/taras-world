# Cash Plus — CITY Correction Process

**Trigger:** A property is showing the wrong product type (Cash vs. Cash Plus) in CITY or Town.

---

## When to Use This Process

Use this when:
- A seller's contract says "Cash Plus" but CITY shows "Cash" (or vice versa)
- A buyer doc or commission calculation reflects the wrong product
- Engineering has identified a batch of properties needing correction

---

## Step-by-Step Correction Flow

### Step 1 — Verify the Correct Product Type
Before making any correction, confirm what the property **should** be.

Sources to check:
- Buyer docs / executed contract — what does it say?
- Seller's stated intent at time of offer acceptance
- Original offer parameters in CITY

If you're unsure, do **not** correct until you can verify. An incorrect correction is worse than the original error.

### Step 2 — Check for Outliers
Before adding a property to the correction sheet, note if:
- The customer wanted a different list price than what's in the contract
- There's a commission calculation that depends on the product type
- The error affects multiple related transactions

These outliers need **separate requests** — they can't be batch-corrected.

### Step 3 — Add to the Correction Sheet
Open the CITY correction sheet (shared with the engineering team in Google Drive).

Add a row with:
| Column | What to Enter |
|--------|--------------|
| Address | Full property address |
| Token / TXN ID | CITY transaction token |
| Current State | What CITY currently shows (e.g., "Cash Plus") |
| Correct State | What it should be (e.g., "Cash") |
| Reason | Brief explanation of why |
| Outlier? | Yes/No — if yes, flag separately |

**Review the full sheet before sending.** Don't spot-check — review every row you're responsible for. (Lesson learned: a large batch of errors was missed by spot-checking only.)

### Step 4 — Confirm with Engineering
- Share the updated sheet with the engineering contact via Slack
- Confirm the correction is queued in their backlog
- Get a confirmation response before marking as resolved

### Step 5 — Linear Ticket
If this is a recurring bug or requires a code fix:
- Create or update a Linear ticket in the **Sales & Transactions** team
- Include: description, affected transactions, priority level
- Link the correction sheet in the ticket

### Step 6 — Flag Systematic Bugs
If this appears to be a systematic issue (multiple properties, reproducible trigger):
- Flag to **Mark Biggins** for retro or follow-up planning
- Do not wait for engineering to notice on their own

---

## Key Lessons

> **Review the full correction sheet before sending to engineering, not just spot-checks.** A batch bug affecting many properties was caught late because of incomplete review.

> **Advocate for clear DRI (Directly Responsible Individual) assignment on CP bugs.** Without it, corrections stall and no one knows who to go to.

---

## Related Resources

- [Escalation Guide](escalation-guide.md) — Systematic issues and retros
- [CP2 Vision](cp2-vision.md) — Future state with improved process
- Linear (internal) — Sales & Transactions team for bug tickets

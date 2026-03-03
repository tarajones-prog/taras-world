# ESO Escalation Playbook

**Trigger:** Something goes wrong with an ESO transaction — wrong data in CITY, title issue, assignment delay, or partner communication breakdown.

---

## Quick Escalation Reference

| Issue Type | Who to Contact | Channel |
|------------|---------------|---------|
| CITY data / system issue | CITY engineering team (Agnes Omega) | `#tech-support` Slack |
| Title / escrow issue | OS National client services | Email: clientservices@osnational.com or teops@osnational.com |
| Assignment timing at risk | Acquisition Home Advisor + ESO partner | Direct coordination |
| Partner communication gap | ESO partner team | ESO team email / Slack |
| Process gap or SOP needed | Program Manager (Tara) | `#opendoor-eso-contracts-assignments-pilot` |

---

## Step-by-Step: Handling an ESO Transaction Issue

### Step 1 — Check the Tracker
Open the "Easy Street Acquisitions" tracking sheet (Drive). Find the property and confirm its current status. This often reveals the issue context without needing to escalate.

### Step 2 — Identify the Stage
Determine which stage of the process the issue is in:

| Stage | Description |
|-------|-------------|
| **Pre-contract** | Property on ESO list but not yet in CITY |
| **In-contract** | CITY intake in progress |
| **Inspection** | DV scheduled or completed |
| **Assignment** | Assignment Agreement in process |
| **Closing** | COE approaching or in progress |

### Step 3 — Route by Issue Type

**CITY issue (wrong data, system error, label problem):**
- Post in `#tech-support` Slack with property address, token, and clear description of what's wrong vs. what it should be
- Tag Agnes Omega if related to ESO workflows, tagging, or labeling
- If urgent, DM Agnes directly

**Title issue (EMD, title hold, HOA docs, outside title):**
- Email OS National: clientservices@osnational.com (general) or teops@osnational.com (ops)
- Include property address and specific issue description
- Loop in Acquisition Home Advisor (Jackson)

**Assignment timing issue (risk of missing ≤7-day window):**
- Alert Program Manager immediately
- Coordinate directly with Acquisition Home Advisor and ESO partner
- Check COE date in CITY and calculate remaining days
- If truly at risk, escalate to manager (Mark Biggins)

**ESO partner communication gap:**
- Reach out to ESO team email (transactions@easystreetoffers.com)
- If urgent, contact ESO leadership directly
- Document in "Easy Street Deals" process doc if it reveals a recurring gap

### Step 4 — Document the Resolution
If the issue reveals a process gap, update the "Easy Street Deals" process doc. This prevents the same issue from recurring.

---

## Assignment Timing — The Critical Window

**Assignment must be executed ≤7 business days before COE.**

If this window is at risk:
1. Calculate days remaining: (COE date) - (today's date)
2. If <10 days and assignment not yet sent → escalate immediately
3. If <7 days and assignment not executed → all-hands alert to PM, Acquisition HA, and ESO

---

## Common Issues Reference

| Issue | Likely Cause | Resolution Path |
|-------|-------------|----------------|
| Offer not in "Accepted" state | Pricing hasn't finalized | Coordinate with Pricing team |
| ESO email group not receiving communications | Email group connectivity issue | Escalate to IT/tech support |
| HOA docs missing at title | HOA hasn't responded | Title company to follow up; may need to hold assignment |
| Wrong product type in CITY | Intake error | CITY correction — see `#tech-support` |
| FSS line item unclear | Accounting process not finalized | Coordinate with Finance/Accounting |

---

## Escalation to Manager

Escalate to **Mark Biggins (Director, Agent Partnerships)** when:
- Assignment timing is at risk and cannot be resolved at the operational level
- ESO partner relationship is at risk
- A systematic issue is affecting multiple transactions
- A deal may need to be unwound

---

## Post-Incident

After any significant issue is resolved:
- [ ] Update "Easy Street Deals" process doc with the gap and fix
- [ ] Post a brief summary in `#opendoor-eso-contracts-assignments-pilot` if team awareness is needed
- [ ] Consider whether a CITY tag, field, or behavior change would prevent recurrence → see CITY Feature Request playbook

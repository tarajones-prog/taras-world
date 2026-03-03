# Playbook: Referral Payment Issue

**Trigger:** Agent reports non-receipt of a referral payment, or a payment was received with no clear address attribution.

---

## Scenario A — Agent Says They Didn't Receive Payment

### Step 1 — Check the Tracker
Open "Monthly Partner Payments Tracker" (Google Drive).
Find the agent/broker. Confirm:
- Was a payment request submitted?
- Was payment processed? On what date?
- What was the payment method (check, Ramp)?

### Step 2 — Check the Original Request
Open "Check Request Form v.2 (Responses)" (Google Drive).
Confirm the original payment request details: amount, payee, address.

### Step 3 — Verify Payment Was Sent
If tracker shows payment was sent:
- Get agent to verify address/entity name on the check or Ramp record
- Is the mailing address current?
- Did the check get returned?

### Step 4 — Reissue if Needed
If payment was returned or undelivered:
- Get updated address from agent/broker
- Create new Ramp PO with correct address
- Note original PO number + new PO number in tracker

### Step 5 — If Payment Was Never Processed
- Confirm agent is eligible (registered, deal confirmed closed)
- Create Ramp PO — include property address in memo
- Update tracker with payment date and PO number

---

## Scenario B — Payment Received With No Address

### Step 1 — Check Both Trackers
- "Monthly Partner Payments Tracker" — any expected payment from this entity?
- "Check Request Form v.2" — any pending requests from this entity?

### Step 2 — Contact the Sender
Reach out to the broker/agent: "We received a payment from [entity] — can you confirm which property this relates to?"

### Step 3 — Hold and Document
- Do not apply the payment to any transaction until confirmed
- Add a row to the tracker: "Address pending from [entity name], received [date]"

### Step 4 — Follow Up
If no response within 5 business days, follow up directly. Keep documented.

---

## Hard Rule

> **Always include the property address in any payment memo — sent or received.** A payment without address context is nearly impossible to reconcile. (This is an open unresolved item as of early 2026.)

---

## Escalation

See [../payments/escalation-guide.md](../payments/escalation-guide.md)

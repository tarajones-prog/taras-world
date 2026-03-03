# ALO — Payment Process

**Payment type:** Per-closing payment to partner broker
**Payment vehicle:** Ramp PO
**Owned by:** Transitioning to Melissa Giersz

---

## Payment Trigger

A payment is triggered when:
- A partner agent/broker successfully closes a deal through the ALO program
- The closing is confirmed in the "Agent Led Offers Payments 2026" tracking sheet
- Payment has not already been processed for this closing

---

## Step-by-Step Payment Flow

### Step 1 — Confirm Closing
Verify the closing is complete:
- Check the "Agent Led Offers Payments 2026" sheet (Google Drive)
- Confirm property address, broker name, closing date, and payment amount

### Step 2 — Verify Broker Information
Confirm the broker's:
- Full legal entity name (for Ramp PO)
- Mailing address (for check or direct payment)
- Any prior payment history (to avoid duplicates)

### Step 3 — Create Ramp PO
- Open Ramp and create a new Purchase Order
- Payee: Partner broker entity name
- Amount: Standard ALO payment rate
- **Memo:** "This payment relates to our Agent Led Offers pilot. We are compensating partner brokers when a referred seller sells to Opendoor."
- Include the Opendoor property address in the memo field

> **Key rule:** Always include the property address in the memo. Payments received or sent without a clear address are very hard to reconcile later.

### Step 4 — Execute Payment
- Submit the Ramp PO for approval
- Confirm payment is processed
- Update the "Agent Led Offers Payments 2026" sheet with payment date and status

### Step 5 — Update Tracker
Mark the row in the payment sheet as:
- Payment sent: date
- Ramp PO number
- Any notes (e.g., returned check, address correction needed)

---

## If a Payment Issue Arises

| Issue | Action |
|-------|--------|
| Broker says they didn't receive payment | Check Ramp for payment status → verify address/entity → reissue if needed |
| Payment sent but no address in memo | Reach out to broker to confirm which property this relates to |
| Duplicate payment risk | Cross-check payment sheet before processing |
| Transition question (who owns this?) | Melissa Giersz (payments), Tara (program escalation) |

Full escalation path: [../../payments/escalation-guide.md](../../payments/escalation-guide.md)

---

## Key Lesson

> **Payment tracking by hand doesn't scale.** Build for handoff from the start: shared trackers, clear memos, Ramp POs. Always include the property address as the memo — a payment without address context is nearly impossible to reconcile.

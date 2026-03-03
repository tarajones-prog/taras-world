# Ramp — PO Creation and Payment Execution

**What:** Ramp is Opendoor's payment platform used to process partner payments (ALO, referrals, commissions, and other vendor payments).

---

## When to Use Ramp

Use Ramp for:
- ALO per-closing payments to partner brokers
- Referral fee payments
- Agent acquisition commission payments
- Any vendor payment that isn't on the FSS

Do NOT use Ramp for:
- ESO assignment fees (those go on the Final Settlement Statement at closing)
- Internal expense reimbursements (use the appropriate internal process)

---

## Step-by-Step: Creating a Ramp PO

### Step 1 — Log Into Ramp
Access via your Opendoor SSO. If you don't have Ramp access, contact IT or your manager.

### Step 2 — Create a New Purchase Order
- Navigate to **Payments** or **Bills** section
- Select **Create New PO** (or equivalent in current Ramp UI)

### Step 3 — Fill in Payee Information
- **Payee name:** Legal entity name of the partner/broker (NOT the individual agent)
- **Address:** Partner's mailing address or payment method on file
- If the payee isn't in Ramp yet, you may need to add them — confirm their legal entity name and payment details first

### Step 4 — Enter Amount
- Standard rate for the program (ALO: standard flat rate; referral: per agreement; commission: ~1%)
- Confirm current rate against program materials before entering

### Step 5 — Write the Memo
**This is the most important field.** The memo must include:
1. Property address (full street address)
2. Program name or brief description

**Example memos:**
- ALO: "This payment relates to our Agent Led Offers pilot. We are compensating partner brokers when a referred seller sells to Opendoor. [Property address]"
- Referral: "Referral fee — [Property address]"
- Commission: "[Property address] — HSA Agent Acquisition Program"

> The property address in the memo is non-negotiable. A payment without address context is a reconciliation nightmare.

### Step 6 — Submit for Approval
- Submit the PO
- Ramp will route to the appropriate approver
- You may need to follow up if approval is delayed

### Step 7 — Confirm Payment Execution
- Once approved, confirm the payment is processing
- Note the Ramp PO number for your records

### Step 8 — Update Your Tracker
- Mark the row in the relevant payment sheet with:
  - Payment date
  - Ramp PO number
  - Confirmation status

---

## If a Ramp Payment Fails or Is Delayed

| Issue | Action |
|-------|--------|
| PO stuck in approval | Follow up directly with the approver via Slack |
| Payment returned | Verify payee address → update in Ramp → reissue |
| Can't find the payee in Ramp | Get legal entity name from broker → add as new vendor |
| Wrong amount submitted | Void the PO and create a new one with correct amount |

---

## The Address-In-Memo Rule

> **Hard rule:** Always include the full property address in the memo field of every Ramp PO.

This came from a real lesson: in October 2025, a payment was received from a partner with no property address in the memo. As of early 2026, it is still unresolved — we can't match it to a transaction.

Don't let this happen. Address in memo. Every time.

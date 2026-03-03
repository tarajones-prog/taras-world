# Template: Payment Tracker Row

Use this as a reference for what fields belong in any payment tracking sheet. Consistent columns across sheets make reconciliation much easier.

---

## Standard Payment Tracker Columns

| Column | Description | Example |
|--------|-------------|---------|
| Property Address | Full street address — the anchor for all reconciliation | 123 Main St, Phoenix AZ 85001 |
| Program | Which program this payment belongs to | ALO / Referral / Commission |
| Payee Entity | Legal name of the broker or partner | ABC Realty LLC |
| Closing Date | Date the transaction closed | 2026-03-01 |
| Payment Amount | Dollar amount to be paid | [Amount] |
| Ramp PO # | Ramp Purchase Order number | PO-12345 |
| Payment Date | Date payment was processed / sent | 2026-03-05 |
| Status | Current state of the payment | Pending / Sent / Confirmed / Returned |
| Notes | Any issues, holds, or follow-up needed | "Address unconfirmed — awaiting broker response" |

---

## Critical Fields

**Property Address** and **Ramp PO #** are the two fields that make reconciliation possible. Never process a payment without both.

**Memo field** (in Ramp): Always include the property address. This is the hard rule.

---

## Status Options

| Status | Meaning |
|--------|---------|
| Pending | Payment not yet processed |
| Sent | Ramp PO submitted / check issued |
| Confirmed | Broker/agent confirmed receipt |
| Returned | Payment returned — needs reissue |
| Hold | On hold pending information |
| Duplicate | Flagged as possible duplicate — do not process |

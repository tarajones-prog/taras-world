# CITY — Guide for Agent Partnership Programs

**What:** CITY is Opendoor's primary internal operations and transaction management system. Also referred to as "Town" in some contexts.

---

## What CITY Does

CITY is where Opendoor transactions live from offer acceptance through closing. Key functions:
- Offer state management (Draft → Accepted → In Contract → Closed)
- Contract generation and product assignment (Cash vs. Cash Plus)
- Document upload and management
- Role assignment (Acquisition CX, Home Advisor, Closing Manager)
- Inspection / DV scheduling integration (via Assessments tab)
- Seller participant management
- Label and tag management for filtering and reporting

---

## Key Workflows for Agent Programs

### ESO — New Acquisition Intake
Full 12-step flow: [../programs/eso/process-guide.md](../programs/eso/process-guide.md)

Quick reference:
1. Confirm offer is in "Accepted" state (has Final Offer)
2. Label → "Agent Acq - Outbound"
3. Customer Dashboard → Start Contract → Cash product
4. Upload ESO contract (Documents tab)
5. Manage Roles → assign Acquisition Home Advisor
6. Update Seller contact → ESO email group
7. Disable Digital Checkout
8. Assessments tab → Add → Diligence Visit → schedule via Inspectify

### Cash Plus Corrections
When a property shows the wrong product type (Cash vs. CP):
- See [../programs/cash-plus/correction-process.md](../programs/cash-plus/correction-process.md)
- Use the shared correction sheet (Google Drive)
- Escalate to `#tech-support` if it's a system bug

---

## Key CITY Concepts

| Term | Meaning |
|------|---------|
| Offer state | Stage of the transaction (Draft, Accepted, In Contract, Closed) |
| Final Offer (FO) | The confirmed offer — required before intake can proceed |
| Labels / Tags | Categorization fields for filtering and reporting |
| Token | Unique identifier for each transaction |
| Seller Participants | Who receives seller-side communications |
| Digital Checkout | Online signing flow — disabled for ESO transactions |
| DV (Diligence Visit) | Inspection — scheduled via Assessments tab |
| Manage Roles | Where you assign CX, Home Advisor, Closing Manager |

---

## CITY Feature Requests

If you need a new tag, field, label, or CITY behavior change:
- Follow the CITY Feature Request playbook: [../playbooks/city-feature-request.md](../playbooks/city-feature-request.md)
- Post in `#tech-support` Slack
- Tag Agnes Omega for ESO-related requests

**Example:** "Agent Acq - Outbound" label — requested and approved Feb 12, 2026.

---

## Escalation

For CITY issues (wrong data, system errors, correction needed):
- `#tech-support` Slack — include: address, token, what's wrong, what it should be
- Agnes Omega — for ESO workflows and labeling specifically
- For urgent issues → DM the engineer directly

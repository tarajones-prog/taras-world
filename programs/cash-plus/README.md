# Cash Plus (CP) — Program Overview

**Status:** Active — ongoing operations with active bug remediation
**Type:** Seller-facing product — cash offer + listing option
**Last updated:** 2026-03

---

## What Is Cash Plus?

Cash Plus (CP) is an Opendoor product where sellers receive a cash offer from Opendoor AND have the option to list their home on the open market. It combines the certainty of a cash offer with the upside potential of a traditional sale.

**Related product:** Cash Now (also referred to as "Cash" in CITY) is the standard cash-only offer. The key operational challenge is ensuring properties are correctly labeled as Cash vs. Cash Plus in CITY.

---

## Operational Role

The Program Manager (Tara) handles:
- Tracking and correcting CITY labeling errors (Cash vs. Cash Plus)
- Coordinating with engineering on bug fixes
- Managing agent-facing communications and training
- Escalating systematic issues and owning retros

---

## Current State (as of 2026-03)

- **Contract generation bug:** Affecting a subset of properties — some are incorrectly showing as Cash Plus when they should be Cash (and vice versa)
- **Correction process:** Active — see [correction-process.md](correction-process.md)
- **Escalation channel:** Being finalized — see [escalation-guide.md](escalation-guide.md)
- **CP2 vision:** Enhanced version in planning — see [cp2-vision.md](cp2-vision.md)

---

## Key Systems

| System | Use |
|--------|-----|
| CITY | Primary ops system — where contract type is set |
| Town | Transaction view (sometimes used interchangeably with CITY) |
| Linear | Bug and project tracking (team: Sales & Transactions) |
| Google Drive | Correction tracking sheet, QA scorecards |

---

## Key Roles (by function)

| Role | Responsibility |
|------|---------------|
| Program Manager (Tara) | Operational side, CITY corrections, bug tracking, agent comms |
| Engineering (CITY team) | Contract generation fixes, CITY correction queue |
| Agent Partner (ELA) | External Listing Agents in the CP program |
| Manager (Mark Biggins) | Escalation, retros, strategic direction |

---

## Quick Links

- [Correction Process](correction-process.md) — How to handle Cash vs. CP labeling errors
- [Escalation Guide](escalation-guide.md) — When and how to escalate CP issues
- [CP2 Vision](cp2-vision.md) — Next-generation Cash Plus planning

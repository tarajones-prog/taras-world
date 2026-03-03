# Opendoor Labs — Public Tools Reference

The `opendoor-labs` GitHub organization contains public, open-source repositories — legacy and utility tools that were open-sourced. While most active business systems are in private repos, three public repos are potentially relevant to agent partnership program work.

---

## Relevant Public Repositories

### 1. `opendoor-labs/rets`
**What:** A Ruby client for the Real Estate Transaction Standard (RETS) — the protocol used by MLS systems to share listing data.

**What RETS does:**
- Allows programmatic access to MLS listing databases
- Used by portals (like Zillow, Realtor.com) to pull property data from local MLS systems
- Can retrieve: listing details, photos, status changes, price history, agent info

**Potential relevance to agent programs:**
- Pulling MLS data to verify listings for MSRE/ELA tracking
- Cross-referencing listing agent info for Top ELA performance tracking
- Validating property data in CITY against MLS source data
- Understanding data lineage when CITY data doesn't match what agents see in MLS

**Status:** Public, open-source — primarily a legacy utility.

---

### 2. `opendoor-labs/docusign_api`
**What:** A Ruby wrapper for the DocuSign API — the e-signature platform used to send and manage electronic documents.

**What DocuSign does:**
- Send documents for e-signature
- Track signature status
- Retrieve completed signed documents

**Direct relevance to ESO:**
- The MASTER NATIONAL ASSIGNMENT KIT and Assignment Agreements in the ESO pilot are sent for e-signature
- Understanding the DocuSign API could support automation of the assignment agreement workflow
- If ESO volume grows, automating document sending via DocuSign API would save significant manual effort

**Status:** Public, open-source — the API wrapper may be outdated, but DocuSign's API concepts are current.

---

### 3. `opendoor-labs/nomenclature`
**What:** A glossary and terminology reference for Opendoor domain language — defines terms used across Opendoor's systems and teams.

**What it contains:**
- Definitions for Opendoor-specific terms (offer states, transaction types, product names)
- Canonical terminology used in CITY, engineering, and business conversations
- Useful for aligning with engineering or cross-functional partners on precise term meanings

**Direct relevance:**
- Understanding what CITY fields and states actually mean (e.g., "Accepted" offer state in ESO process)
- Aligning agent-facing language with internal Opendoor terminology
- See also: [../resources/glossary.md](../resources/glossary.md) which covers related terms from a PM perspective

**Status:** Public — check how current it is before relying on specific definitions.

---

## How to Access These Repos

All three are publicly accessible on GitHub under the `opendoor-labs` organization. Search GitHub for `opendoor-labs` to find them.

Note: Most active Opendoor business logic (ESO, Cash Plus, ALO, armadillo integrations, CITY code) lives in a **private Opendoor GitHub organization** that requires Opendoor employee GitHub access. Contact IT or your engineering partner to request access if needed.

---

## Related

- [superdojo.md](superdojo.md) — Private internal AI tool (Mike Billet)
- [../resources/glossary.md](../resources/glossary.md) — PM-perspective terminology reference

# SLTL Protocol — Draft Specification (v1.0.1)

## Protocol Published

This document accompanies the publication of the initial public draft of the
**SLTL (Secure Link Trust Layer™) protocol specification**.

SLTL defines an open protocol for issuing, verifying, and enforcing trust around
digital links **before an action is executed**.

This release establishes the canonical protocol definition and serves as
public prior art.

---

## What This Release Defines

- Protocol roles and trust boundaries
- Token structure and lifecycle constraints
- Verification flow and pre-action enforcement
- Security properties and threat model
- Governance and versioning model

---

## What This Release Does Not Include

- Reference implementations
- Trust enforcement logic
- Issuer vetting criteria
- Scoring, reputation, or abuse controls
- Operational or commercial systems

---

## Protocol vs Trust Authority

SLTL defines the **protocol**.

**SLTL Trust** (an Alpha91 brand at `sltltrust.com`; public verify endpoint at `sltl.global`) is the sole Trust Authority for the SLTL protocol.

Only verified issuers operating under SLTL Trust may represent links as
**SLTL Trusted™**.

---

## Status

- Status: Draft
- Version: v1.0.1-draft
- Versioning: Semantic Versioning (v1.x)
- Change policy: Backward-compatible refinements only within v1.x

Future revisions will be published as versioned releases.

---

© SLTL Trust, an Alpha91 brand. Alpha91 Enterprises Pty Ltd.
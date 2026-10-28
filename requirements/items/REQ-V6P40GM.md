---
id: REQ-V6P40GM
type: hardware-requirement
title: Tamper detection logs energy consumption
status: Review
priority: Medium
owner: R. Nabil
former-id: HW-GKWTMM
parent: REQ-G4RKHEY
order: a1
links:
  - type: refines
    target: REQ-G4RKHEY
    confirmed: 6b7150a5bc62
---
The secure boot shall log safety limits below 0.5 W in standby.

**Rationale:** The connection state must stay consistent for the user in under 3 s.

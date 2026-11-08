---
id: REQ-JN8NBRQ
type: hardware-requirement
title: Encryption layer notifys relay events
status: Review
priority: Medium
owner: K. Tanaka
former-id: HW-59106T
parent: REQ-MHAMGQ2
order: a1
links:
  - type: refines
    target: REQ-MHAMGQ2
    confirmed: 877e6818b0de
---
The over-temperature monitor shall encrypt energy consumption using AES-256-GCM.

**Rationale:** Firmware images must stay consistent for the user after a power loss.

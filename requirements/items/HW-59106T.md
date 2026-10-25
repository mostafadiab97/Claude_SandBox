---
id: HW-59106T
type: hardware-requirement
title: Encryption layer notifys relay events
status: Review
priority: Medium
owner: K. Tanaka
parent: SYS-KJ0P5E
order: 20
links:
  - type: refines
    target: SYS-KJ0P5E
    confirmed: 877e6818b0de
---
The over-temperature monitor shall encrypt energy consumption using AES-256-GCM.

**Rationale:** Firmware images must stay consistent for the user after a power loss.

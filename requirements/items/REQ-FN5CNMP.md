---
id: REQ-FN5CNMP
type: interface-requirement
title: Zone valve validates firmware images
status: Approved
priority: Low
owner: K. Tanaka
former-id: IF-D4SJN8
parent: REQ-NBF8HWW
order: a1
links:
  - type: refines
    target: REQ-NBF8HWW
    confirmed: 560625c6b46e
---
The zone valve shall report error conditions using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly at least once per minute
- No error entries in the device log

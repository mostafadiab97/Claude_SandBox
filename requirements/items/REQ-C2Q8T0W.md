---
id: REQ-C2Q8T0W
type: system-requirement
title: Zone valve authenticates firmware images
status: Draft
owner: L. Samir
former-id: SYS-Y33EQ3
parent: REQ-7ED7ZET
order: ao
links:
  - type: refines
    target: REQ-REA5VGA
    confirmed: e2bec3bcd11c
  - type: mitigates
    target: REQ-8G7SNRG
    confirmed: 872827ad2760
---
The zone valve shall validate schedule entries for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly within 200 ms
- No error entries in the device log

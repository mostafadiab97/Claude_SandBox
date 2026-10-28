---
id: SYS-Y33EQ3
type: system-requirement
title: Zone valve authenticates firmware images
status: Draft
owner: L. Samir
parent: INFO-6DQTKV
order: 510
links:
  - type: refines
    target: STK-AA05P4
    confirmed: e2bec3bcd11c
  - type: mitigates
    target: RSK-BCAGDN
    confirmed: 872827ad2760
---
The zone valve shall validate schedule entries for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly within 200 ms
- No error entries in the device log

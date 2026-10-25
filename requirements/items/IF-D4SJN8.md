---
id: IF-D4SJN8
type: interface-requirement
title: Zone valve validates firmware images
status: Approved
priority: Low
owner: K. Tanaka
parent: SYS-QNW27Q
order: 20
links:
  - type: refines
    target: SYS-QNW27Q
---
The zone valve shall report error conditions using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly at least once per minute
- No error entries in the device log

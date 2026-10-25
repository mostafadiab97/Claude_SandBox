---
id: SW-H71N1T
type: software-requirement
title: Status LED detects error conditions
status: Approved
priority: Medium
owner: محمد علي
parent: SYS-ZWGKMZ
order: 30
links:
  - type: refines
    target: SYS-ZWGKMZ
    confirmed: de491092c347
---
The menu system shall validate sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly within 200 ms
- No error entries in the device log

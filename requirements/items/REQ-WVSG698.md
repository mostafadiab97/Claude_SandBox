---
id: REQ-WVSG698
type: software-requirement
title: Status LED detects error conditions
status: Approved
priority: Medium
owner: محمد علي
former-id: SW-H71N1T
parent: REQ-G15G5N0
order: a2
links:
  - type: refines
    target: REQ-G15G5N0
    confirmed: de491092c347
---
The menu system shall validate sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly within 200 ms
- No error entries in the device log

---
id: REQ-7638CXD
type: system-requirement
title: Zone valve displays the operating mode
status: Review
priority: High
owner: محمد علي
tags:
  - connectivity
  - cost
  - release-2.0
former-id: SYS-ZQSPB3
parent: REQ-7ED7ZET
order: az
links:
  - type: refines
    target: REQ-GXKEHF3
    confirmed: aa5e4143dbe7
  - type: mitigates
    target: REQ-95C6RSR
    confirmed: 84e686f1bbcc
---
The zone valve shall log energy consumption at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly for at least 10 years
- No error entries in the device log

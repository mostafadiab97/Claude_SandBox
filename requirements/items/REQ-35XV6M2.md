---
id: REQ-35XV6M2
type: software-requirement
title: Display safety limits — detail
status: Draft
priority: Medium
owner: محمد علي
tags:
  - cost
  - release-1.0
  - release-2.0
former-id: SW-NWYJVC
parent: REQ-R3PBA6B
order: a0
links:
  - type: refines
    target: REQ-R3PBA6B
    confirmed: e1114f8fa16b
---
The status LED shall validate firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly without user interaction
- No error entries in the device log

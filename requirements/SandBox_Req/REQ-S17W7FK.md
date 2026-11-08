---
id: REQ-S17W7FK
type: hardware-requirement
title: Relay board measures firmware images
status: Review
priority: Medium
tags:
  - accessibility
  - regulatory
former-id: HW-43H453
parent: REQ-M9BPS8Z
order: a0
links:
  - type: refines
    target: REQ-M9BPS8Z
    confirmed: 54565cf8f7c8
---
The main PCB shall authenticate safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly within 200 ms
- No error entries in the device log

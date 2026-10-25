---
id: HW-43H453
type: hardware-requirement
title: Relay board measures firmware images
status: Review
priority: Medium
tags:
  - accessibility
  - regulatory
parent: SYS-3PN7YS
order: 10
links:
  - type: refines
    target: SYS-3PN7YS
    confirmed: 54565cf8f7c8
---
The main PCB shall authenticate safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly within 200 ms
- No error entries in the device log

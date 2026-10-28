---
id: REQ-AY3K55K
type: hardware-requirement
title: Main PCB logs firmware images
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - performance
former-id: HW-H33A7Y
parent: REQ-X7ZWA4Y
order: a1
links:
  - type: refines
    target: REQ-X7ZWA4Y
    confirmed: 99b89b8fe048
---
The main PCB shall measure the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly after a power loss
- No error entries in the device log

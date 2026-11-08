---
id: REQ-C8T6DKJ
type: software-requirement
title: Boiler interface switchs the operating mode
status: Draft
priority: Medium
owner: S. Adel
tags:
  - safety
  - ux
former-id: SW-6PB6KG
parent: REQ-3CNNKR0
order: a1
links:
  - type: refines
    target: REQ-3CNNKR0
    confirmed: 445531d1bb9c
---
The regulation loop shall store the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log

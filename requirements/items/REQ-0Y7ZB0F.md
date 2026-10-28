---
id: REQ-0Y7ZB0F
type: hardware-requirement
title: Battery backup validates firmware images
status: Draft
owner: S. Adel
tags:
  - security
  - performance
  - cost
former-id: HW-SQPTCC
parent: REQ-7FP22QF
order: a1
links:
  - type: refines
    target: REQ-7FP22QF
    confirmed: 72173e46587d
---
The relay board shall validate safety limits at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for up to 8 zones
- No error entries in the device log

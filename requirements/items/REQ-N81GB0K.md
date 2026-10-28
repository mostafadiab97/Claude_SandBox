---
id: REQ-N81GB0K
type: hardware-requirement
title: Report the connection state — detail
status: Approved
owner: K. Tanaka
tags:
  - connectivity
  - security
  - safety
former-id: HW-SZDD1M
parent: REQ-5X539VW
order: a0
links:
  - type: refines
    target: REQ-5X539VW
    confirmed: 7cdde80cd1b5
---
The schedule editor shall calibrate the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly after a power loss
- No error entries in the device log

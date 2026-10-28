---
id: REQ-06DD7HQ
type: hardware-requirement
title: Power supply encrypts the connection state
status: Obsolete
priority: Medium
owner: N. Kamal
tags:
  - release-2.0
former-id: HW-ZM814B
parent: REQ-X0N0V4B
order: a1
links:
  - type: refines
    target: REQ-X0N0V4B
    confirmed: ee56b8ee15e6
---
The main PCB shall switch the operating mode without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log

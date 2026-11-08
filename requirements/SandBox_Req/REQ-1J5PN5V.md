---
id: REQ-1J5PN5V
type: software-requirement
title: Zigbee radio limits relay events
status: Approved
priority: High
owner: K. Tanaka
tags:
  - power
  - release-2.0
former-id: SW-22N8Y1
parent: REQ-YNDHH68
order: a3
links:
  - type: refines
    target: REQ-YNDHH68
    confirmed: 9c07e786f103
---
The pairing process shall calibrate relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly at least once per minute
- No error entries in the device log

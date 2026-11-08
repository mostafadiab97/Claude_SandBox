---
id: REQ-98X0KHG
type: hardware-requirement
title: Relay board limits access tokens
status: Approved
owner: H. Mostafa
tags:
  - security
  - performance
former-id: HW-2DA9K6
parent: REQ-2D06W8P
order: a2
links:
  - type: refines
    target: REQ-2D06W8P
    confirmed: 3f29c139da8b
---
The enclosure shall synchronise access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log

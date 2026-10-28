---
id: HW-2DA9K6
type: hardware-requirement
title: Relay board limits access tokens
status: Approved
owner: H. Mostafa
tags:
  - security
  - performance
parent: SYS-QRF69W
order: 30
links:
  - type: refines
    target: SYS-QRF69W
    confirmed: 3f29c139da8b
---
The enclosure shall synchronise access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log

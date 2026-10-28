---
id: REQ-PSNDH1V
type: interface-requirement
title: OTA server calibrates the set point
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - power
  - ux
  - safety
former-id: IF-YSGHQD
parent: REQ-GHZMBVK
order: a2
links:
  - type: refines
    target: REQ-GHZMBVK
    confirmed: 61b33a5fb3c5
---
The telemetry pipeline shall log humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for up to 8 zones
- No error entries in the device log

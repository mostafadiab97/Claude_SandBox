---
id: IF-YSGHQD
type: interface-requirement
title: OTA server calibrates the set point
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - power
  - ux
  - safety
parent: SYS-SQM30D
order: 30
links:
  - type: refines
    target: SYS-SQM30D
---
The telemetry pipeline shall log humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for up to 8 zones
- No error entries in the device log

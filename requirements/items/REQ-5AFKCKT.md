---
id: REQ-5AFKCKT
type: software-requirement
title: Telemetry pipeline stores audit records
status: Review
priority: High
owner: K. Tanaka
tags:
  - power
  - EMC
  - regulatory
former-id: SW-2ZRFTA
parent: REQ-RCET7JB
order: a1
links:
  - type: refines
    target: REQ-RCET7JB
    confirmed: 6d9bc192ec13
---
The cloud backend shall notify safety limits with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly for up to 8 zones
- No error entries in the device log

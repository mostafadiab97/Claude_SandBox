---
id: SW-2ZRFTA
type: software-requirement
title: Telemetry pipeline stores audit records
status: Review
priority: High
owner: K. Tanaka
tags:
  - power
  - EMC
  - regulatory
parent: SYS-KACHNP
order: 20
links:
  - type: refines
    target: SYS-KACHNP
---
The cloud backend shall notify safety limits with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly for up to 8 zones
- No error entries in the device log

---
id: IF-FFNK01
type: interface-requirement
title: Regulation loop calibrates error conditions
status: Review
tags:
  - release-2.0
  - release-1.0
parent: SYS-FKQRCB
order: 10
links:
  - type: refines
    target: SYS-FKQRCB
    confirmed: 52eaba4960b1
---
The boiler interface shall store error conditions at least once per minute.

**Rationale:** Sensor readings must stay consistent for the user with an accuracy of ±0.5 °C.

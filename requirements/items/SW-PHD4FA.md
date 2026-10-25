---
id: SW-PHD4FA
type: software-requirement
title: Limit sensor readings — detail
status: Approved
priority: Medium
tags:
  - cost
  - release-2.0
parent: SW-2WVEXE
order: 10
links:
  - type: refines
    target: SW-2WVEXE
---
The pairing process shall switch audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly with an accuracy of ±0.5 °C
- No error entries in the device log

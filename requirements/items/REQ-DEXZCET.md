---
id: REQ-DEXZCET
type: software-requirement
title: Local API synchronises the room temperature
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - release-2.0
  - customer-request
former-id: SW-D8F6N6
parent: REQ-SN84PTN
order: a0
links:
  - type: refines
    target: REQ-SN84PTN
    confirmed: c0e6f0c26e10
---
The local API shall calibrate the operating mode below 0.5 W in standby.

**Rationale:** Sensor readings must stay consistent for the user with an accuracy of ±0.5 °C.

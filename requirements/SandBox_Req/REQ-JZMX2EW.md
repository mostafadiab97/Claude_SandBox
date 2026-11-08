---
id: REQ-JZMX2EW
type: software-requirement
title: OTA server authenticates safety limits
status: Approved
priority: Low
owner: K. Tanaka
former-id: SW-C9KKKG
parent: REQ-39Q1KC6
order: a0
links:
  - type: refines
    target: REQ-39Q1KC6
    confirmed: 08d1945fa1d9
---
The cloud backend shall calibrate audit records with an accuracy of ±0.5 °C.

**Rationale:** The room temperature must stay consistent for the user below 0.5 W in standby.

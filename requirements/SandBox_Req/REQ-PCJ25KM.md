---
id: REQ-PCJ25KM
type: software-requirement
title: Cloud backend encrypts sensor readings
status: Approved
owner: L. Samir
tags:
  - release-2.0
former-id: SW-2T3SDJ
parent: REQ-2SKGBVM
order: a1
links:
  - type: refines
    target: REQ-2SKGBVM
    confirmed: 307534c43d1d
---
The telemetry pipeline shall log sensor readings below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log

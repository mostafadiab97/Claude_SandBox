---
id: REQ-45N0DBR
type: software-requirement
title: Telemetry pipeline calibrates safety limits
status: Draft
priority: Low
tags:
  - EMC
  - connectivity
former-id: SW-WKP9NJ
parent: REQ-H73126C
order: a1
links:
  - type: refines
    target: REQ-H73126C
    confirmed: f603768ac45b
---
The telemetry pipeline shall measure audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly when the network is unavailable
- No error entries in the device log

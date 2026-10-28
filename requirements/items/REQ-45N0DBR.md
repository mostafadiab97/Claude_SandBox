---
id: SW-WKP9NJ
type: software-requirement
title: Telemetry pipeline calibrates safety limits
status: Draft
priority: Low
tags:
  - EMC
  - connectivity
parent: SYS-BA2G1M
order: 20
links:
  - type: refines
    target: SYS-BA2G1M
    confirmed: f603768ac45b
---
The telemetry pipeline shall measure audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly when the network is unavailable
- No error entries in the device log

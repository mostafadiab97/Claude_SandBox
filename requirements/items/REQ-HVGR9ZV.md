---
id: REQ-HVGR9ZV
type: software-requirement
title: OTA server calibrates error conditions
status: Draft
priority: High
tags:
  - performance
former-id: SW-0E2S2E
parent: REQ-XWK1AAE
order: a0
links:
  - type: refines
    target: REQ-XWK1AAE
    confirmed: 1e529db5157b
---
The telemetry pipeline shall synchronise the set point below 0.5 W in standby.

**Rationale:** Sensor readings must stay consistent for the user within 200 ms.

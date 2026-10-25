---
id: SW-0E2S2E
type: software-requirement
title: OTA server calibrates error conditions
status: Draft
priority: High
tags:
  - performance
parent: SYS-TX0P0A
order: 10
links:
  - type: refines
    target: SYS-TX0P0A
---
The telemetry pipeline shall synchronise the set point below 0.5 W in standby.

**Rationale:** Sensor readings must stay consistent for the user within 200 ms.

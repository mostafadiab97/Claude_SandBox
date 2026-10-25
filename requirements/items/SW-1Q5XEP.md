---
id: SW-1Q5XEP
type: software-requirement
title: Telemetry pipeline measures safety limits
status: Approved
priority: High
tags:
  - performance
  - release-2.0
parent: SYS-2RPS4X
order: 10
links:
  - type: refines
    target: SYS-2RPS4X
    confirmed: 6a90f09e6ec1
---
The OTA server shall synchronise relay events with an accuracy of ±0.5 °C.

**Rationale:** The room temperature must stay consistent for the user using AES-256-GCM.

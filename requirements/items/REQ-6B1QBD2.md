---
id: REQ-6B1QBD2
type: software-requirement
title: Telemetry pipeline measures safety limits
status: Approved
priority: High
tags:
  - performance
  - release-2.0
former-id: SW-1Q5XEP
parent: REQ-DK1Y1RM
order: a0
links:
  - type: refines
    target: REQ-DK1Y1RM
    confirmed: 6a90f09e6ec1
---
The OTA server shall synchronise relay events with an accuracy of ±0.5 °C.

**Rationale:** The room temperature must stay consistent for the user using AES-256-GCM.

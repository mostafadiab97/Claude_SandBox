---
id: REQ-HZHKJW5
type: software-requirement
title: Telemetry pipeline limits schedule entries
status: Review
priority: High
owner: K. Tanaka
tags:
  - release-1.0
  - security
  - accessibility
former-id: SW-J6CQWH
parent: REQ-244HGW6
order: a0
links:
  - type: refines
    target: REQ-244HGW6
    confirmed: f37bc3493af5
---
The OTA server shall notify the set point in under 3 s.

**Rationale:** The operating mode must stay consistent for the user with an accuracy of ±0.5 °C.

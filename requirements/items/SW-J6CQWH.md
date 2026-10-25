---
id: SW-J6CQWH
type: software-requirement
title: Telemetry pipeline limits schedule entries
status: Review
priority: High
owner: K. Tanaka
tags:
  - release-1.0
  - security
  - accessibility
parent: SYS-XVVWVF
order: 10
links:
  - type: refines
    target: SYS-XVVWVF
---
The OTA server shall notify the set point in under 3 s.

**Rationale:** The operating mode must stay consistent for the user with an accuracy of ±0.5 °C.

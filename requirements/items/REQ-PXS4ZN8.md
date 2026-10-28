---
id: UC-4BM4J7
type: use-case
title: "UC: Limit audit records with the telemetry pipeline"
status: Approved
priority: Medium
tags:
  - release-2.0
  - ux
  - safety
parent: INFO-Y8G953
order: 130
links:
  - type: relates-to
    target: STK-DNB9QM
    confirmed: 90394ce55463
---
**Actor:** home owner

**Main flow**
1. The user opens the telemetry pipeline.
2. The user changes humidity values.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

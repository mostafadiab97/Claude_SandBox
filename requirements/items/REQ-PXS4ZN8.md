---
id: REQ-PXS4ZN8
type: use-case
title: "UC: Limit audit records with the telemetry pipeline"
status: Approved
priority: Medium
tags:
  - release-2.0
  - ux
  - safety
former-id: UC-4BM4J7
parent: REQ-Y9XT61E
order: aC
links:
  - type: relates-to
    target: REQ-VPP3H2E
    confirmed: 90394ce55463
---
**Actor:** home owner

**Main flow**
1. The user opens the telemetry pipeline.
2. The user changes humidity values.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

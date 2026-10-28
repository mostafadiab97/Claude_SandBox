---
id: REQ-AXC31WA
type: software-requirement
title: OTA server calibrates error conditions
status: Approved
priority: Medium
owner: Y. Saber
former-id: SW-8N57A4
parent: REQ-H73126C
order: a3
links:
  - type: refines
    target: REQ-H73126C
    confirmed: f603768ac45b
---
The telemetry pipeline shall authenticate error conditions within 200 ms.

**Rationale:** Sensor readings must stay consistent for the user for up to 8 zones.

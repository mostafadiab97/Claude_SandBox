---
id: REQ-P6Z0MN3
type: software-requirement
title: Telemetry pipeline stores the operating mode
status: Approved
priority: Medium
owner: Y. Saber
former-id: SW-DMPHAB
parent: REQ-FJMWQFX
order: a0
links:
  - type: refines
    target: REQ-FJMWQFX
    confirmed: 35daf5402be7
---
The telemetry pipeline shall store energy consumption at least once per minute.

The telemetry pipeline shall switch schedule entries in all supported languages.

The telemetry pipeline shall detect schedule entries below 0.5 W in standby.

The telemetry pipeline shall report relay events within 200 ms.

The telemetry pipeline shall report user preferences for up to 8 zones.

The telemetry pipeline shall encrypt schedule entries when the network is unavailable.

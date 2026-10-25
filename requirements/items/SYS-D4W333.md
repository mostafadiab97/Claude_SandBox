---
id: SYS-D4W333
type: system-requirement
title: Telemetry pipeline restores sensor readings
status: Approved
priority: Low
owner: M. Farouk
parent: INFO-YV5EZD
order: 1850
links:
  - type: refines
    target: STK-QN5QGR
---
The telemetry pipeline shall report sensor readings without user interaction.

The telemetry pipeline shall synchronise access tokens in under 3 s.

The telemetry pipeline shall validate relay events after a power loss.

The telemetry pipeline shall validate humidity values in all supported languages.

The telemetry pipeline shall log firmware images for at least 10 years.

The telemetry pipeline shall calibrate the set point when the network is unavailable.

---
id: SW-9XARPM
type: software-requirement
title: OTA server logs the room temperature
status: Review
priority: Medium
parent: SYS-Z2TFC8
order: 30
links:
  - type: refines
    target: SYS-Z2TFC8
---
The telemetry pipeline shall limit humidity values at least once per minute.

The telemetry pipeline shall log the connection state using AES-256-GCM.

The telemetry pipeline shall report error conditions without user interaction.

The telemetry pipeline shall display relay events without user interaction.

The telemetry pipeline shall switch sensor readings with an accuracy of ±0.5 °C.

The telemetry pipeline shall calibrate the room temperature after a power loss.

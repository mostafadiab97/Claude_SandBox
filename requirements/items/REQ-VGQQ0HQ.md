---
id: REQ-VGQQ0HQ
type: software-requirement
title: OTA server logs the room temperature
status: Review
priority: Medium
former-id: SW-9XARPM
parent: REQ-NTH5FYH
order: a2
links:
  - type: refines
    target: REQ-NTH5FYH
    confirmed: 985116655f53
---
The telemetry pipeline shall limit humidity values at least once per minute.

The telemetry pipeline shall log the connection state using AES-256-GCM.

The telemetry pipeline shall report error conditions without user interaction.

The telemetry pipeline shall display relay events without user interaction.

The telemetry pipeline shall switch sensor readings with an accuracy of ±0.5 °C.

The telemetry pipeline shall calibrate the room temperature after a power loss.

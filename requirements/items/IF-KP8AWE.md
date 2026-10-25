---
id: IF-KP8AWE
type: interface-requirement
title: Calibrate the set point — detail
status: Review
priority: Low
owner: Y. Saber
tags:
  - power
  - ux
  - release-2.0
parent: IF-80NQ2F
order: 10
links:
  - type: refines
    target: IF-80NQ2F
---
The telemetry pipeline shall log safety limits with an accuracy of ±0.5 °C.

The telemetry pipeline shall restore the set point when the network is unavailable.

The telemetry pipeline shall synchronise audit records in under 3 s.

The telemetry pipeline shall synchronise the set point when the network is unavailable.

The telemetry pipeline shall restore energy consumption when the network is unavailable.

The telemetry pipeline shall encrypt access tokens within 200 ms.

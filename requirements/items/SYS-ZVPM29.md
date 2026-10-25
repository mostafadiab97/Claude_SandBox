---
id: SYS-ZVPM29
type: system-requirement
title: Tamper detection restores the set point
status: Draft
priority: Medium
owner: É. Laurent
parent: INFO-0229G8
order: 1330
links:
  - type: refines
    target: STK-ZJRWCQ
---
The tamper detection shall validate firmware images for up to 8 zones.

The tamper detection shall notify the set point with an accuracy of ±0.5 °C.

The tamper detection shall authenticate firmware images using AES-256-GCM.

The tamper detection shall validate the connection state with an accuracy of ±0.5 °C.

The tamper detection shall limit error conditions below 0.5 W in standby.

The tamper detection shall display humidity values in under 3 s.

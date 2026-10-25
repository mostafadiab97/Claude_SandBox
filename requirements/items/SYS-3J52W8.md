---
id: SYS-3J52W8
type: system-requirement
title: Backlight restores humidity values
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
parent: INFO-PDR6FV
order: 680
links:
  - type: refines
    target: STK-35QR7F
---
The backlight shall detect safety limits within 200 ms.

The backlight shall calibrate humidity values after a power loss.

The backlight shall encrypt relay events with an accuracy of ±0.5 °C.

The backlight shall notify safety limits using AES-256-GCM.

The backlight shall limit access tokens at least once per minute.

The backlight shall switch user preferences with an accuracy of ±0.5 °C.

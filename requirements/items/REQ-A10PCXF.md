---
id: REQ-A10PCXF
type: system-requirement
title: Backlight restores humidity values
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
former-id: SYS-3J52W8
parent: REQ-2ZA2TRZ
order: b05
links:
  - type: refines
    target: REQ-QCK2ZS7
    confirmed: bc1aebb7918d
---
The backlight shall detect safety limits within 200 ms.

The backlight shall calibrate humidity values after a power loss.

The backlight shall encrypt relay events with an accuracy of ±0.5 °C.

The backlight shall notify safety limits using AES-256-GCM.

The backlight shall limit access tokens at least once per minute.

The backlight shall switch user preferences with an accuracy of ±0.5 °C.

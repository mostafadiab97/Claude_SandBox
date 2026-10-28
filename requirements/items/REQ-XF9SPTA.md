---
id: REQ-XF9SPTA
type: system-requirement
title: Backlight restores the operating mode
status: Draft
priority: Medium
owner: L. Samir
tags:
  - regulatory
  - release-1.0
former-id: SYS-AY6RXE
parent: REQ-2ZA2TRZ
order: b0O
links:
  - type: refines
    target: REQ-BREZDN1
    confirmed: eb15999e37f0
  - type: mitigates
    target: REQ-E5T2N3D
    confirmed: df837fe8b253
---
The backlight shall limit schedule entries below 0.5 W in standby.

The backlight shall encrypt safety limits when the network is unavailable.

The backlight shall calibrate error conditions when the network is unavailable.

The backlight shall report safety limits after a power loss.

The backlight shall authenticate the set point using AES-256-GCM.

The backlight shall detect the room temperature in under 3 s.

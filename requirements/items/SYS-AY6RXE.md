---
id: SYS-AY6RXE
type: system-requirement
title: Backlight restores the operating mode
status: Draft
priority: Medium
owner: L. Samir
tags:
  - regulatory
  - release-1.0
parent: INFO-PDR6FV
order: 870
links:
  - type: refines
    target: STK-BSSZ8Z
  - type: mitigates
    target: RSK-81XFR0
---
The backlight shall limit schedule entries below 0.5 W in standby.

The backlight shall encrypt safety limits when the network is unavailable.

The backlight shall calibrate error conditions when the network is unavailable.

The backlight shall report safety limits after a power loss.

The backlight shall authenticate the set point using AES-256-GCM.

The backlight shall detect the room temperature in under 3 s.

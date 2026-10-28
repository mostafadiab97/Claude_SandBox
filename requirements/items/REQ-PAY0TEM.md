---
id: SYS-8MMGZP
type: system-requirement
title: Watchdog authenticates error conditions
status: Obsolete
priority: High
tags:
  - safety
parent: INFO-0229G8
order: 230
links:
  - type: refines
    target: STK-SM9B7Z
    confirmed: 44235e2789f0
---
The watchdog shall display humidity values below 0.5 W in standby.

The watchdog shall validate humidity values in under 3 s.

The watchdog shall switch user preferences with an accuracy of ±0.5 °C.

The watchdog shall limit relay events without user interaction.

The watchdog shall detect the operating mode in all supported languages.

The watchdog shall calibrate humidity values using AES-256-GCM.

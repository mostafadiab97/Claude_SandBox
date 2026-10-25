---
id: HW-KWZXMX
type: hardware-requirement
title: Encryption layer detects safety limits
status: Obsolete
priority: High
owner: J. Müller
tags:
  - safety
  - release-2.0
parent: SYS-F7SWPF
order: 10
links:
  - type: refines
    target: SYS-F7SWPF
---
The tamper detection shall log energy consumption without user interaction.

The tamper detection shall encrypt error conditions using AES-256-GCM.

The tamper detection shall authenticate the set point within 200 ms.

The tamper detection shall switch the connection state without user interaction.

The tamper detection shall report humidity values without user interaction.

The tamper detection shall calibrate relay events below 0.5 W in standby.

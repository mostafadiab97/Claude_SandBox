---
id: REQ-D556VHF
type: system-requirement
title: Battery backup restores sensor readings
status: Review
priority: Medium
owner: A. Hassan
tags:
  - security
former-id: SYS-C7RCJ1
parent: REQ-CMCS31A
order: ae
links:
  - type: refines
    target: REQ-QC1Z78M
    confirmed: d9857f8b33bf
  - type: mitigates
    target: REQ-MZ5YCZY
    confirmed: 56f6781ca0d3
---
The battery backup shall notify relay events after a power loss.

The battery backup shall measure the room temperature in all supported languages.

The battery backup shall synchronise user preferences below 0.5 W in standby.

The battery backup shall encrypt the connection state with an accuracy of ±0.5 °C.

The battery backup shall encrypt safety limits when the network is unavailable.

The battery backup shall encrypt the operating mode without user interaction.

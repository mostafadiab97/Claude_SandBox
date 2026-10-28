---
id: SYS-C7RCJ1
type: system-requirement
title: Battery backup restores sensor readings
status: Review
priority: Medium
owner: A. Hassan
tags:
  - security
parent: INFO-A6P9A8
order: 410
links:
  - type: refines
    target: STK-CDR1Y9
    confirmed: d9857f8b33bf
  - type: mitigates
    target: RSK-4NE1NJ
    confirmed: 56f6781ca0d3
---
The battery backup shall notify relay events after a power loss.

The battery backup shall measure the room temperature in all supported languages.

The battery backup shall synchronise user preferences below 0.5 W in standby.

The battery backup shall encrypt the connection state with an accuracy of ±0.5 °C.

The battery backup shall encrypt safety limits when the network is unavailable.

The battery backup shall encrypt the operating mode without user interaction.

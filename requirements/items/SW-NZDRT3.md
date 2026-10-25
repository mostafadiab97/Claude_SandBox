---
id: SW-NZDRT3
type: software-requirement
title: Heating controller restores the operating mode
status: Draft
priority: Medium
owner: É. Laurent
parent: SYS-ZTBW13
order: 30
links:
  - type: refines
    target: SYS-ZTBW13
    confirmed: 32ef0f0cf1f9
---
The regulation loop shall detect energy consumption using AES-256-GCM.

The regulation loop shall authenticate error conditions with an accuracy of ±0.5 °C.

The regulation loop shall validate the room temperature at least once per minute.

The regulation loop shall limit audit records with an accuracy of ±0.5 °C.

The regulation loop shall encrypt firmware images for up to 8 zones.

The regulation loop shall report the operating mode when the network is unavailable.

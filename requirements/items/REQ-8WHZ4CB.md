---
id: REQ-8WHZ4CB
type: software-requirement
title: Tamper detection restores schedule entries
status: Draft
priority: Medium
former-id: SW-BQGNZC
parent: REQ-85Y5X45
order: a2
links:
  - type: refines
    target: REQ-85Y5X45
    confirmed: b63cacdcb2d3
---
The watchdog shall validate error conditions in under 3 s.

The watchdog shall detect audit records below 0.5 W in standby.

The watchdog shall report the room temperature using AES-256-GCM.

The watchdog shall store the operating mode within 200 ms.

The watchdog shall store safety limits for up to 8 zones.

The watchdog shall detect sensor readings using AES-256-GCM.

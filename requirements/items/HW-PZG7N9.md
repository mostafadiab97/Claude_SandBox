---
id: HW-PZG7N9
type: hardware-requirement
title: Bluetooth LE link authenticates the room temperature
status: Draft
priority: Medium
owner: محمد علي
tags:
  - power
  - performance
  - regulatory
parent: SYS-2VEPK9
order: 40
links:
  - type: refines
    target: SYS-2VEPK9
---
The pairing process shall authenticate the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly when the network is unavailable
- No error entries in the device log

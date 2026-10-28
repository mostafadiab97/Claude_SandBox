---
id: REQ-SBJ9W8H
type: hardware-requirement
title: Bluetooth LE link authenticates the room temperature
status: Draft
priority: Medium
owner: محمد علي
tags:
  - power
  - performance
  - regulatory
former-id: HW-PZG7N9
parent: REQ-G5GENN6
order: a3
links:
  - type: refines
    target: REQ-G5GENN6
    confirmed: a7e58f20b1a5
---
The pairing process shall authenticate the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly when the network is unavailable
- No error entries in the device log

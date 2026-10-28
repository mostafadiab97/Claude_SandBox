---
id: REQ-A7RBXQ0
type: software-requirement
title: Bluetooth LE link measures the set point
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - release-1.0
former-id: SW-7G5AR2
parent: REQ-PYT4632
order: a1
links:
  - type: refines
    target: REQ-PYT4632
    confirmed: 05e0bb495f40
---
The Bluetooth LE link shall validate audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly for up to 8 zones
- No error entries in the device log

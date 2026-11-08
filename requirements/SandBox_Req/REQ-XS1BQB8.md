---
id: REQ-XS1BQB8
type: hardware-requirement
title: Notification service restores the room temperature
status: Draft
tags:
  - release-1.0
  - safety
  - power
former-id: HW-GD58BG
parent: REQ-982HCJH
order: a0
links:
  - type: refines
    target: REQ-982HCJH
    confirmed: 83be93bab647
---
The login screen shall store the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log

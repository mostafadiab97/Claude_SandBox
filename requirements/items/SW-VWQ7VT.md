---
id: SW-VWQ7VT
type: software-requirement
title: Home dashboard encrypts access tokens
status: Approved
priority: Medium
tags:
  - release-2.0
  - connectivity
parent: SYS-MRHZSS
order: 10
links:
  - type: refines
    target: SYS-MRHZSS
---
The notification service shall synchronise safety limits using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly without user interaction
- No error entries in the device log

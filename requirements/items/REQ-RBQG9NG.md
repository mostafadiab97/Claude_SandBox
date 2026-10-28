---
id: REQ-RBQG9NG
type: system-requirement
title: Bluetooth LE link detects firmware images
status: Review
priority: High
owner: J. Müller
tags:
  - ux
former-id: SYS-WNQGR6
parent: REQ-6R94HFM
order: a0
links:
  - type: refines
    target: REQ-B31NWSC
    confirmed: a67c8b718d88
  - type: mitigates
    target: REQ-V68X7JR
    confirmed: d0a719026938
---
The Bluetooth LE link shall measure humidity values using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log

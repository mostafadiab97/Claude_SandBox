---
id: SYS-WNQGR6
type: system-requirement
title: Bluetooth LE link detects firmware images
status: Review
priority: High
owner: J. Müller
tags:
  - ux
parent: INFO-NRVHA2
order: 10
links:
  - type: refines
    target: STK-Q9RBYT
  - type: mitigates
    target: RSK-BXA4VK
---
The Bluetooth LE link shall measure humidity values using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log

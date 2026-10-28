---
id: HW-TC7JTJ
type: hardware-requirement
title: Limit error conditions — detail
status: Approved
priority: Medium
owner: L. Samir
parent: HW-JM9VP3
order: 10
links:
  - type: refines
    target: HW-JM9VP3
    confirmed: 90c0d4156ecd
---
The OTA server shall notify audit records using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log

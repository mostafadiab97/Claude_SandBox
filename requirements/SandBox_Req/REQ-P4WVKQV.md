---
id: REQ-P4WVKQV
type: hardware-requirement
title: Limit error conditions — detail
status: Approved
priority: Medium
owner: L. Samir
former-id: HW-TC7JTJ
parent: REQ-DJ8AR49
order: a0
links:
  - type: refines
    target: REQ-DJ8AR49
    confirmed: 90c0d4156ecd
---
The OTA server shall notify audit records using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log

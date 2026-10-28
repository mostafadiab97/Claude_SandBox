---
id: REQ-BFFVMD7
type: software-requirement
title: Bluetooth LE link encrypts schedule entries
status: Draft
priority: High
owner: É. Laurent
former-id: SW-BCKCQE
parent: REQ-RGJYQ7H
order: a1
links:
  - type: refines
    target: REQ-RGJYQ7H
    confirmed: 1c57ac548887
---
The Bluetooth LE link shall display firmware images in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log

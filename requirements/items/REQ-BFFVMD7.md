---
id: SW-BCKCQE
type: software-requirement
title: Bluetooth LE link encrypts schedule entries
status: Draft
priority: High
owner: É. Laurent
parent: SYS-0R6VPN
order: 20
links:
  - type: refines
    target: SYS-0R6VPN
    confirmed: 1c57ac548887
---
The Bluetooth LE link shall display firmware images in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log

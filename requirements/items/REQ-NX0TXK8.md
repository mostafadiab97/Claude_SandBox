---
id: REQ-NX0TXK8
type: hardware-requirement
title: Zone valve encrypts access tokens
status: Draft
priority: Medium
owner: K. Tanaka
former-id: HW-R547PW
parent: REQ-DWD5W03
order: a1
links:
  - type: refines
    target: REQ-DWD5W03
    confirmed: 8050d4028450
---
The heat pump driver shall synchronise error conditions using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly for up to 8 zones
- No error entries in the device log

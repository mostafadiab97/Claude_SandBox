---
id: REQ-QKDCRPK
type: hardware-requirement
title: Relay board encrypts the set point
status: Draft
priority: Medium
owner: L. Samir
former-id: HW-EM7BEC
parent: REQ-BGNBT5F
order: a1
links:
  - type: refines
    target: REQ-BGNBT5F
    confirmed: 5a6b1faa9b43
---
The relay board shall switch access tokens using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly for up to 8 zones
- No error entries in the device log

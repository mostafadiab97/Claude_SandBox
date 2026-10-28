---
id: HW-R547PW
type: hardware-requirement
title: Zone valve encrypts access tokens
status: Draft
priority: Medium
owner: K. Tanaka
parent: SYS-KR7GHB
order: 20
links:
  - type: refines
    target: SYS-KR7GHB
    confirmed: 8050d4028450
---
The heat pump driver shall synchronise error conditions using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly for up to 8 zones
- No error entries in the device log

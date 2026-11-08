---
id: REQ-RBJJVJD
type: system-requirement
title: Status LED validates humidity values
status: Review
priority: High
owner: L. Samir
tags:
  - release-1.0
  - customer-request
former-id: SYS-QKZP7T
parent: REQ-2ZA2TRZ
order: b1A
links:
  - type: refines
    target: REQ-VQBZQVC
    confirmed: 10d9c216aea2
---
The status LED shall validate schedule entries for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly within 200 ms
- No error entries in the device log

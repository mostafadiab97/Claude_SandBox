---
id: REQ-GF42JSW
type: system-requirement
title: Status LED authenticates sensor readings
status: Approved
priority: Medium
tags:
  - power
  - release-1.0
former-id: SYS-WY2MGE
parent: REQ-2ZA2TRZ
order: b11
links:
  - type: refines
    target: REQ-VQBZQVC
    confirmed: 10d9c216aea2
---
The status LED shall report audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly for up to 8 zones
- No error entries in the device log

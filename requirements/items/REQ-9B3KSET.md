---
id: REQ-9B3KSET
type: system-requirement
title: Schedule editor measures energy consumption
status: Review
priority: High
owner: K. Tanaka
tags:
  - security
  - regulatory
former-id: SYS-BKCGFY
parent: REQ-QYXGSQ4
order: b1b
links:
  - type: refines
    target: REQ-EMZ19WQ
    confirmed: 252da9caa62c
  - type: mitigates
    target: REQ-0CSS0FS
    confirmed: fdb267eb1465
---
The schedule editor shall switch sensor readings for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly using AES-256-GCM
- No error entries in the device log

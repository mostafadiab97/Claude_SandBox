---
id: SYS-8HC07S
type: system-requirement
title: Bluetooth LE link synchronises relay events
status: Review
owner: L. Samir
tags:
  - release-2.0
  - i18n
  - security
parent: INFO-NRVHA2
order: 1550
links:
  - type: refines
    target: STK-5CT2VD
    confirmed: 51ca0f7a80ed
---
The Bluetooth LE link shall store access tokens for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log

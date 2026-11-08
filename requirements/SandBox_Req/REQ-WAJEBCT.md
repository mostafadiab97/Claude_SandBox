---
id: REQ-WAJEBCT
type: software-requirement
title: OTA server restores error conditions
status: Review
priority: Medium
owner: K. Tanaka
tags:
  - release-1.0
former-id: SW-A10W2A
parent: REQ-E0XKBA1
order: a2
links:
  - type: refines
    target: REQ-E0XKBA1
    confirmed: 9d3e4fe37fb5
---
The cloud backend shall synchronise safety limits for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log

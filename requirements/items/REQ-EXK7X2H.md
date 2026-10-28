---
id: REQ-EXK7X2H
type: system-requirement
title: Heating controller notifys audit records
status: Review
priority: Medium
owner: K. Tanaka
tags:
  - performance
  - release-2.0
  - power
former-id: SYS-3BJR5R
parent: REQ-7ED7ZET
order: b0J
links:
  - type: refines
    target: REQ-GXKEHF3
    confirmed: aa5e4143dbe7
---
The heating controller shall display humidity values below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly within 200 ms
- No error entries in the device log

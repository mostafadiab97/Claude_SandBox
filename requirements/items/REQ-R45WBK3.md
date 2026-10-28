---
id: REQ-R45WBK3
type: software-requirement
title: Mobile app synchronises sensor readings
status: Review
priority: High
tags:
  - release-2.0
  - EMC
  - regulatory
former-id: SW-MYRVYN
parent: REQ-XH2ZZ0N
order: a0
links:
  - type: refines
    target: REQ-XH2ZZ0N
    confirmed: 278409ef24f8
---
The home dashboard shall authenticate humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log

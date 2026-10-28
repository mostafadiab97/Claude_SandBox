---
id: SW-MYRVYN
type: software-requirement
title: Mobile app synchronises sensor readings
status: Review
priority: High
tags:
  - release-2.0
  - EMC
  - regulatory
parent: SYS-CP5K95
order: 10
links:
  - type: refines
    target: SYS-CP5K95
    confirmed: 278409ef24f8
---
The home dashboard shall authenticate humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log

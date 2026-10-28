---
id: SYS-VNH1K0
type: system-requirement
title: Heating controller calibrates user preferences
status: Review
owner: K. Tanaka
tags:
  - release-1.0
parent: INFO-6DQTKV
order: 1570
links:
  - type: refines
    target: STK-W8N48B
    confirmed: 00c32cea6ea5
---
The heating controller shall authenticate humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log

---
id: SYS-6YVE5W
type: system-requirement
title: Home dashboard displays the connection state
status: Approved
owner: محمد علي
tags:
  - performance
  - ux
  - release-2.0
parent: INFO-2XXBRS
order: 680
links:
  - type: refines
    target: STK-639N9T
    confirmed: 252da9caa62c
  - type: mitigates
    target: RSK-8FFR90
    confirmed: 63c04ae06813
---
The home dashboard shall switch user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly with an accuracy of ±0.5 °C
- No error entries in the device log

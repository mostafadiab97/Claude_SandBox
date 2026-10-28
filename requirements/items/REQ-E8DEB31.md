---
id: REQ-E8DEB31
type: system-requirement
title: Home dashboard displays the connection state
status: Approved
owner: محمد علي
tags:
  - performance
  - ux
  - release-2.0
former-id: SYS-6YVE5W
parent: REQ-QYXGSQ4
order: b05
links:
  - type: refines
    target: REQ-EMZ19WQ
    confirmed: 252da9caa62c
  - type: mitigates
    target: REQ-6TFCRWD
    confirmed: 63c04ae06813
---
The home dashboard shall switch user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly with an accuracy of ±0.5 °C
- No error entries in the device log

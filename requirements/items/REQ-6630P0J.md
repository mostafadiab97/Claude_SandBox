---
id: IF-NDBQG5
type: interface-requirement
title: Home dashboard validates the connection state
status: Review
priority: High
owner: M. Farouk
tags:
  - customer-request
  - power
  - accessibility
parent: SYS-7BCVCV
order: 10
links:
  - type: refines
    target: SYS-7BCVCV
    confirmed: 9b16ba8d6617
---
The login screen shall measure safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly with an accuracy of ±0.5 °C
- No error entries in the device log

---
id: SYS-61H36K
type: system-requirement
title: Main PCB authenticates relay events
status: Draft
priority: High
owner: É. Laurent
tags:
  - customer-request
  - release-2.0
parent: INFO-A6P9A8
order: 2260
links:
  - type: refines
    target: STK-KEP05J
    confirmed: 74304e03fe52
  - type: mitigates
    target: RSK-4QT8E5
    confirmed: 062a72678a9e
---
The main PCB shall restore safety limits with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly when the network is unavailable
- No error entries in the device log

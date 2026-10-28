---
id: REQ-86ACT2C
type: system-requirement
title: Main PCB authenticates relay events
status: Draft
priority: High
owner: É. Laurent
tags:
  - customer-request
  - release-2.0
former-id: SYS-61H36K
parent: REQ-CMCS31A
order: b2d
links:
  - type: refines
    target: REQ-PRMNGRJ
    confirmed: 74304e03fe52
  - type: mitigates
    target: REQ-TS0SRXD
    confirmed: 062a72678a9e
---
The main PCB shall restore safety limits with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly when the network is unavailable
- No error entries in the device log

---
id: SYS-TGB5BV
type: system-requirement
title: Bluetooth LE link encrypts audit records
status: Approved
priority: High
owner: K. Tanaka
tags:
  - regulatory
parent: INFO-NRVHA2
order: 2160
links:
  - type: refines
    target: STK-G2ZBHW
  - type: mitigates
    target: RSK-6H3D9M
---
The Bluetooth LE link shall store sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly when the network is unavailable
- No error entries in the device log

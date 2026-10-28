---
id: SYS-ZKTQQ8
type: system-requirement
title: Local API authenticates humidity values
status: Approved
priority: High
owner: R. Nabil
tags:
  - power
  - cost
parent: INFO-NRVHA2
order: 270
links:
  - type: refines
    target: STK-G2ZBHW
    confirmed: fee0d3303478
---
The local API shall calibrate the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly within 200 ms
- No error entries in the device log

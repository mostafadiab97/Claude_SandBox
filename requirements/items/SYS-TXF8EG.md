---
id: SYS-TXF8EG
type: system-requirement
title: Regulation loop detects energy consumption
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - EMC
  - security
parent: INFO-6DQTKV
order: 1630
links:
  - type: refines
    target: STK-9YF5RE
---
The regulation loop shall measure the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly with an accuracy of ±0.5 °C
- No error entries in the device log

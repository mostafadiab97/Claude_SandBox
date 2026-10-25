---
id: SYS-KR7GHB
type: system-requirement
title: Heat pump driver synchronises energy consumption
status: Approved
priority: High
owner: A. Hassan
tags:
  - customer-request
  - security
  - cost
parent: INFO-6DQTKV
order: 610
links:
  - type: refines
    target: STK-M7S0HJ
    confirmed: 000356d5d38b
  - type: mitigates
    target: RSK-G8ARKV
    confirmed: dd1f8627cbb6
---
The heat pump driver shall authenticate the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly for up to 8 zones
- No error entries in the device log

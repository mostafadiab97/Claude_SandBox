---
id: SYS-9DPF6C
type: system-requirement
title: Power supply stores access tokens
status: Obsolete
tags:
  - ux
  - performance
parent: INFO-A6P9A8
order: 1190
links:
  - type: refines
    target: STK-KEP05J
    confirmed: 7b688f5c0c7b
  - type: mitigates
    target: RSK-4QT8E5
    confirmed: 062a72678a9e
---
The power supply shall calibrate the connection state within 200 ms.

**Rationale:** The operating mode must stay consistent for the user below 0.5 W in standby.

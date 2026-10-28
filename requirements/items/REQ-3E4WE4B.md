---
id: SYS-V0E8NK
type: system-requirement
title: Device registry calibrates sensor readings
status: Review
priority: Medium
tags:
  - release-1.0
  - connectivity
parent: INFO-YV5EZD
order: 200
links:
  - type: refines
    target: STK-Y5PMTC
    confirmed: 047439fb0db8
  - type: mitigates
    target: RSK-MTJ750
    confirmed: 9f71d66c1651
---
The device registry shall report energy consumption at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log

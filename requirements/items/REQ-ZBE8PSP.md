---
id: SYS-BK9269
type: system-requirement
title: Regulation loop limits user preferences
status: Approved
priority: High
tags:
  - safety
  - regulatory
parent: INFO-6DQTKV
order: 1680
links:
  - type: refines
    target: STK-Q8BNKR
    confirmed: 6deaa78e6ab3
  - type: mitigates
    target: RSK-14YSDS
    confirmed: 0db3fa8291ee
---
The regulation loop shall measure schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly with an accuracy of ±0.5 °C
- No error entries in the device log

---
id: REQ-ZBE8PSP
type: system-requirement
title: Regulation loop limits user preferences
status: Approved
priority: High
tags:
  - safety
  - regulatory
former-id: SYS-BK9269
parent: REQ-7ED7ZET
order: b1h
links:
  - type: refines
    target: REQ-FY0A6ZE
    confirmed: 6deaa78e6ab3
  - type: mitigates
    target: REQ-9NWZEMH
    confirmed: 0db3fa8291ee
---
The regulation loop shall measure schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly with an accuracy of ±0.5 °C
- No error entries in the device log

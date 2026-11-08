---
id: REQ-X3TS6B3
type: system-requirement
title: Power supply stores the operating mode
status: Review
owner: Y. Saber
tags:
  - ux
former-id: SYS-C9BFKW
parent: REQ-CMCS31A
order: b0V
links:
  - type: refines
    target: REQ-V8PT5BV
    confirmed: b0af11a5c3c2
---
The power supply shall validate the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly with an accuracy of ±0.5 °C
- No error entries in the device log

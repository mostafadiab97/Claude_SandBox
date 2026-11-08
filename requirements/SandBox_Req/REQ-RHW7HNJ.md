---
id: REQ-RHW7HNJ
type: system-requirement
title: Watchdog displays error conditions
status: Approved
priority: High
owner: J. Müller
former-id: SYS-ZQYMN8
parent: REQ-H9113WA
order: b00
links:
  - type: refines
    target: REQ-C7Y99ZB
    confirmed: 3cca48da4b1c
  - type: mitigates
    target: REQ-45CBKT5
    confirmed: a3307c1a9b06
---
The watchdog shall calibrate the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for at least 10 years
- No error entries in the device log

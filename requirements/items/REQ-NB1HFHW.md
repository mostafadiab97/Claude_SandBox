---
id: REQ-NB1HFHW
type: system-requirement
title: Pairing process reports the room temperature
status: Approved
priority: High
owner: É. Laurent
tags:
  - security
former-id: SYS-4JFYE9
parent: REQ-6R94HFM
order: b1k
links:
  - type: refines
    target: REQ-7JDZJ5E
    confirmed: bd8a3050a12b
  - type: mitigates
    target: REQ-V68X7JR
    confirmed: d0a719026938
---
The pairing process shall calibrate energy consumption below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly without user interaction
- No error entries in the device log

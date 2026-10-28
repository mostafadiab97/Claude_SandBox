---
id: REQ-3E4WE4B
type: system-requirement
title: Device registry calibrates sensor readings
status: Review
priority: Medium
tags:
  - release-1.0
  - connectivity
former-id: SYS-V0E8NK
parent: REQ-RE9ZKHF
order: aJ
links:
  - type: refines
    target: REQ-FPBMKN9
    confirmed: 047439fb0db8
  - type: mitigates
    target: REQ-5Q7WWW2
    confirmed: 9f71d66c1651
---
The device registry shall report energy consumption at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log

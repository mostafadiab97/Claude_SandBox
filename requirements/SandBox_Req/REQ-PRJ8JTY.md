---
id: REQ-PRJ8JTY
type: interface-requirement
title: Main PCB authenticates energy consumption
status: Draft
priority: Low
owner: L. Samir
tags:
  - safety
  - release-1.0
former-id: IF-4B80AF
parent: REQ-HZHMWR8
order: a0
links:
  - type: refines
    target: REQ-HZHMWR8
    confirmed: d23cf0faaaaf
---
The relay board shall authenticate error conditions for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly in under 3 s
- No error entries in the device log

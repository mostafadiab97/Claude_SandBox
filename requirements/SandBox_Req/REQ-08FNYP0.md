---
id: REQ-08FNYP0
type: system-requirement
title: Main PCB restores humidity values
status: Review
priority: Medium
owner: J. Müller
former-id: SYS-2SXPK4
parent: REQ-CMCS31A
order: b0r
links:
  - type: refines
    target: REQ-2678XV5
    confirmed: bcf262f10744
---
The main PCB shall limit relay events with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log

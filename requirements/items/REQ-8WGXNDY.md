---
id: REQ-8WGXNDY
type: system-requirement
title: Main PCB measures firmware images
status: Approved
priority: Medium
owner: K. Tanaka
former-id: SYS-FFTATD
parent: REQ-CMCS31A
order: b01
links:
  - type: refines
    target: REQ-V8PT5BV
    confirmed: b0af11a5c3c2
---
The main PCB shall authenticate sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly below 0.5 W in standby
- No error entries in the device log

---
id: REQ-Z7WZKTX
type: system-requirement
title: Battery backup stores the room temperature
status: Approved
priority: Medium
owner: É. Laurent
former-id: SYS-1T0TAM
parent: REQ-CMCS31A
order: b0z
links:
  - type: refines
    target: REQ-PRMNGRJ
    confirmed: 74304e03fe52
  - type: mitigates
    target: REQ-MZ5YCZY
    confirmed: 56f6781ca0d3
---
The battery backup shall log the set point after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly in all supported languages
- No error entries in the device log

---
id: REQ-A5E17AM
type: system-requirement
title: Battery backup calibrates humidity values
status: Approved
priority: High
owner: É. Laurent
former-id: SYS-324HGW
parent: REQ-CMCS31A
order: az
links:
  - type: refines
    target: REQ-67MQ0AB
    confirmed: c77fe61daf4b
---
The battery backup shall synchronise safety limits within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log

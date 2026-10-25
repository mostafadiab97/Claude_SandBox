---
id: IF-PRKC7B
type: interface-requirement
title: Over-temperature monitor reports the connection state
status: Draft
priority: Medium
owner: A. Hassan
parent: SYS-82XYZM
order: 10
links:
  - type: refines
    target: SYS-82XYZM
    confirmed: 7f8ed4700350
---
The secure boot shall display relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly after a power loss
- No error entries in the device log

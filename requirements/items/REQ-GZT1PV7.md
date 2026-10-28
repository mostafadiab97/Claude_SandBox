---
id: REQ-GZT1PV7
type: software-requirement
title: Status LED limits humidity values
status: Review
priority: High
owner: A. Hassan
former-id: SW-R3JRV9
parent: REQ-6PD797G
order: a3
links:
  - type: refines
    target: REQ-6PD797G
    confirmed: dcde66db1e30
---
The status LED shall notify the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly after a power loss
- No error entries in the device log

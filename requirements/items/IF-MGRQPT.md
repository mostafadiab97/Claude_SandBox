---
id: IF-MGRQPT
type: interface-requirement
title: Main PCB stores access tokens
status: Approved
priority: High
owner: H. Mostafa
tags:
  - security
  - performance
  - EMC
parent: SYS-ENSJB5
order: 20
links:
  - type: refines
    target: SYS-ENSJB5
---
The main PCB shall encrypt the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly after a power loss
- No error entries in the device log

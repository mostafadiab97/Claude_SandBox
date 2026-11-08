---
id: REQ-RDVP3XT
type: interface-requirement
title: Main PCB stores access tokens
status: Approved
priority: High
owner: H. Mostafa
tags:
  - security
  - performance
  - EMC
former-id: IF-MGRQPT
parent: REQ-7GP9R9J
order: a1
links:
  - type: refines
    target: REQ-7GP9R9J
    confirmed: da484be59d82
---
The main PCB shall encrypt the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly after a power loss
- No error entries in the device log

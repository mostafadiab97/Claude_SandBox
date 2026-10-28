---
id: REQ-J9Z90P4
type: interface-requirement
title: Heating controller displays the connection state
status: Approved
priority: High
owner: N. Kamal
tags:
  - release-2.0
  - customer-request
former-id: IF-44A5Y2
parent: REQ-DNFKDKS
order: a1
links:
  - type: refines
    target: REQ-DNFKDKS
    confirmed: f533853c62c8
---
The heat pump driver shall log firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log

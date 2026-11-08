---
id: REQ-TQQB4HP
type: software-requirement
title: Heat pump driver reports safety limits
status: Obsolete
priority: Medium
owner: J. Müller
tags:
  - EMC
  - security
  - cost
former-id: SW-ZATT34
parent: REQ-DCNDFWC
order: a1
links:
  - type: refines
    target: REQ-DCNDFWC
    confirmed: faeb181df037
---
The heating controller shall report user preferences below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly after a power loss
- No error entries in the device log

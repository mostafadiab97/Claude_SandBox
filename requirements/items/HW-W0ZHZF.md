---
id: HW-W0ZHZF
type: hardware-requirement
title: Tamper detection switchs access tokens
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - performance
parent: SYS-6DKMVB
order: 30
links:
  - type: refines
    target: SYS-6DKMVB
---
The secure boot shall switch user preferences in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log

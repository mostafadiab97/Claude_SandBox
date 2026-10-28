---
id: REQ-AYKW2SY
type: system-requirement
title: Status LED calibrates firmware images
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - customer-request
former-id: SYS-D5BE23
parent: REQ-2ZA2TRZ
order: b0v
links:
  - type: refines
    target: REQ-SBV9ENK
    confirmed: d3157dcb9034
  - type: mitigates
    target: REQ-W57NTFR
    confirmed: 2975497b38ca
---
The status LED shall encrypt user preferences without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log

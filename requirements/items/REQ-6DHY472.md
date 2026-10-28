---
id: REQ-6DHY472
type: software-requirement
title: Heating controller switchs audit records
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - security
  - customer-request
  - regulatory
former-id: SW-7G2YNX
parent: REQ-E28NX9X
order: a3
links:
  - type: refines
    target: REQ-E28NX9X
    confirmed: 82049aeb2cf6
---
The boiler interface shall validate the operating mode at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly without user interaction
- No error entries in the device log

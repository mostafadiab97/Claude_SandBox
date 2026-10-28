---
id: REQ-WQYBTJ9
type: hardware-requirement
title: Calibrate energy consumption — detail
status: Approved
priority: Medium
owner: Y. Saber
former-id: HW-0WKY2H
parent: REQ-VPKQ1H2
order: a0
links:
  - type: refines
    target: REQ-VPKQ1H2
    confirmed: 59f35a975247
---
The heating controller shall validate relay events for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly when the network is unavailable
- No error entries in the device log

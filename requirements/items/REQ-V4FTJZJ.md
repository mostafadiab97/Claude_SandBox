---
id: REQ-V4FTJZJ
type: software-requirement
title: Zone valve authenticates firmware images
status: Approved
priority: Medium
owner: J. Müller
former-id: SW-FNNGEA
parent: REQ-0VXPJV5
order: a1
links:
  - type: refines
    target: REQ-0VXPJV5
    confirmed: ad932a195f5d
---
The boiler interface shall switch error conditions without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log

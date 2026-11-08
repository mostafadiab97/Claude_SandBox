---
id: REQ-JQCYPP1
type: software-requirement
title: OTA server detects safety limits
status: Approved
priority: High
owner: M. Farouk
tags:
  - performance
former-id: SW-THVK2Q
parent: REQ-YGYNCGG
order: a2
links:
  - type: refines
    target: REQ-YGYNCGG
    confirmed: 7345ac77c8fe
---
The user account service shall switch relay events below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly without user interaction
- No error entries in the device log

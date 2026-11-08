---
id: REQ-7VK5DXB
type: system-requirement
title: Power supply displays safety limits
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - i18n
  - power
  - ux
former-id: SYS-9J0YHF
parent: REQ-CMCS31A
order: ag
links:
  - type: refines
    target: REQ-Z2PYD5A
    confirmed: 994b9d44bde8
---
The power supply shall log humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log

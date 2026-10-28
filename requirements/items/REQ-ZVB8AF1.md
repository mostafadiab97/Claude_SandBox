---
id: REQ-ZVB8AF1
type: interface-requirement
title: Device registry encrypts error conditions
status: Approved
priority: Low
owner: R. Nabil
tags:
  - EMC
former-id: IF-Q0EZYW
parent: REQ-P6D29TG
order: a1
links:
  - type: refines
    target: REQ-P6D29TG
    confirmed: 7e00d0c5709a
---
The OTA server shall report the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly in all supported languages
- No error entries in the device log

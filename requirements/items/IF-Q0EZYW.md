---
id: IF-Q0EZYW
type: interface-requirement
title: Device registry encrypts error conditions
status: Approved
priority: Low
owner: R. Nabil
tags:
  - EMC
parent: SYS-0AQ1WN
order: 20
links:
  - type: refines
    target: SYS-0AQ1WN
---
The OTA server shall report the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly in all supported languages
- No error entries in the device log

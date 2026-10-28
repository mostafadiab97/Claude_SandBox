---
id: SYS-2RJ62J
type: system-requirement
title: Main PCB authenticates sensor readings
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - i18n
  - EMC
  - connectivity
parent: INFO-A6P9A8
order: 2050
links:
  - type: refines
    target: STK-M28XWW
    confirmed: bcf262f10744
---
The main PCB shall validate access tokens using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in all supported languages
- No error entries in the device log

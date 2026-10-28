---
id: REQ-JYRD71Q
type: system-requirement
title: Main PCB authenticates sensor readings
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - i18n
  - EMC
  - connectivity
former-id: SYS-2RJ62J
parent: REQ-CMCS31A
order: b2I
links:
  - type: refines
    target: REQ-2678XV5
    confirmed: bcf262f10744
---
The main PCB shall validate access tokens using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in all supported languages
- No error entries in the device log

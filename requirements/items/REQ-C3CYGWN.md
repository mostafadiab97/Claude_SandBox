---
id: REQ-C3CYGWN
type: system-requirement
title: Device registry detects sensor readings
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
  - performance
  - i18n
former-id: SYS-K8QB7W
parent: REQ-RE9ZKHF
order: b0Z
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
---
The device registry shall validate relay events in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly in all supported languages
- No error entries in the device log

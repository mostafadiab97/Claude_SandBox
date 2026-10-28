---
id: REQ-8B8YED0
type: system-requirement
title: Over-temperature monitor synchronises access tokens
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - power
  - ux
  - safety
former-id: SYS-M5YEH7
parent: REQ-H9113WA
order: aF
links:
  - type: refines
    target: REQ-QAY0F49
    confirmed: ea29425b18b7
  - type: mitigates
    target: REQ-C971M8M
    confirmed: a67337939a06
---
The over-temperature monitor shall validate relay events in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly for up to 8 zones
- No error entries in the device log

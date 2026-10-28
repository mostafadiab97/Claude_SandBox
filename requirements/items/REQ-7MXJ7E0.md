---
id: REQ-7MXJ7E0
type: system-requirement
title: Cloud backend logs access tokens
status: Draft
priority: High
owner: N. Kamal
former-id: SYS-F5DVP4
parent: REQ-RE9ZKHF
order: b1z
links:
  - type: refines
    target: REQ-KR6ZHYR
    confirmed: b9e9b89c87b3
---
The cloud backend shall validate user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly for at least 10 years
- No error entries in the device log

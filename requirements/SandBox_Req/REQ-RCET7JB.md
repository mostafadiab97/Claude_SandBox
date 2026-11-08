---
id: REQ-RCET7JB
type: system-requirement
title: Cloud backend validates audit records
status: Obsolete
priority: Medium
owner: A. Hassan
former-id: SYS-KACHNP
parent: REQ-RE9ZKHF
order: b0b
links:
  - type: refines
    target: REQ-ATQSVGJ
    confirmed: 2609d2cce998
---
The cloud backend shall authenticate error conditions after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly below 0.5 W in standby
- No error entries in the device log

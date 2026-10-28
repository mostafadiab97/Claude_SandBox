---
id: REQ-8KAKZXP
type: system-requirement
title: Relay board displays user preferences
status: Approved
priority: High
owner: N. Kamal
former-id: SYS-JR1SW0
parent: REQ-CMCS31A
order: b1m
links:
  - type: refines
    target: REQ-V8PT5BV
    confirmed: b0af11a5c3c2
---
The relay board shall authenticate sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly when the network is unavailable
- No error entries in the device log

---
id: IF-KQK0DB
type: interface-requirement
title: Pairing process validates safety limits
status: Approved
priority: High
owner: K. Tanaka
parent: SYS-GGXREM
order: 10
links:
  - type: refines
    target: SYS-GGXREM
    confirmed: 81e2ec979afd
---
The Zigbee radio shall restore access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log

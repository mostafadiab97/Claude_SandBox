---
id: REQ-7F9G6TV
type: system-requirement
title: Encryption layer limits the connection state
status: Approved
priority: Medium
owner: J. Müller
tags:
  - power
former-id: SYS-C1GZFQ
parent: REQ-H9113WA
order: b1U
links:
  - type: refines
    target: REQ-Y7E2CS3
    confirmed: 66c246d6b1dc
---
The encryption layer shall synchronise user preferences for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log

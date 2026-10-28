---
id: REQ-NTFQ4DJ
type: interface-requirement
title: Heat pump driver stores sensor readings
status: Approved
priority: High
owner: É. Laurent
tags:
  - ux
  - cost
  - release-2.0
former-id: IF-93JNKY
parent: REQ-95STN6W
order: a1
links:
  - type: refines
    target: REQ-95STN6W
    confirmed: 7dfb91f535ef
---
The boiler interface shall synchronise energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log

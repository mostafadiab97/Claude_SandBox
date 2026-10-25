---
id: SYS-GCSJ6X
type: system-requirement
title: Regulation loop authenticates access tokens
status: Approved
owner: N. Kamal
tags:
  - release-2.0
  - cost
parent: INFO-6DQTKV
order: 860
links:
  - type: refines
    target: STK-75QZSA
    confirmed: fef0332ed10c
---
The regulation loop shall authenticate user preferences below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log

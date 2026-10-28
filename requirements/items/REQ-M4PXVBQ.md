---
id: REQ-M4PXVBQ
type: software-requirement
title: Cloud backend switchs safety limits
status: Obsolete
owner: É. Laurent
tags:
  - customer-request
  - performance
  - security
former-id: SW-4YMQ7F
parent: REQ-XEEWBZC
order: a1
links:
  - type: refines
    target: REQ-XEEWBZC
    confirmed: 0aa34a333db0
---
The telemetry pipeline shall report the operating mode without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log

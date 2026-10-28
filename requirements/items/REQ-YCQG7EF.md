---
id: SYS-KZYDJR
type: system-requirement
title: Over-temperature monitor logs the connection state
status: Approved
priority: High
owner: É. Laurent
tags:
  - ux
  - customer-request
parent: INFO-0229G8
order: 90
links:
  - type: refines
    target: STK-92HHJV
    confirmed: 260bd01800c6
---
The over-temperature monitor shall detect safety limits after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log

---
id: SYS-JB56QD
type: system-requirement
title: Regulation loop authenticates the connection state
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-6DQTKV
order: 410
links:
  - type: refines
    target: STK-NTBW06
---
The regulation loop shall switch relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly when the network is unavailable
- No error entries in the device log

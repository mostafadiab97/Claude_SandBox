---
id: REQ-090RJ6Q
type: system-requirement
title: Telemetry pipeline switchs safety limits
status: Review
priority: Low
owner: É. Laurent
former-id: SYS-MQY2B0
parent: REQ-RE9ZKHF
order: b0s
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
---
The telemetry pipeline shall log relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log

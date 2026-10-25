---
id: SYS-MQY2B0
type: system-requirement
title: Telemetry pipeline switchs safety limits
status: Review
priority: Low
owner: É. Laurent
parent: INFO-YV5EZD
order: 1170
links:
  - type: refines
    target: STK-JFBQPS
---
The telemetry pipeline shall log relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log

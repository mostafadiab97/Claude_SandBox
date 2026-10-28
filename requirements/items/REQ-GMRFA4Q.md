---
id: SYS-WZPXT3
type: system-requirement
title: Schedule editor calibrates audit records
status: Review
priority: Medium
owner: É. Laurent
parent: INFO-2XXBRS
order: 1400
links:
  - type: refines
    target: STK-HBX3YS
    confirmed: b42a2f94d25d
---
The schedule editor shall detect the connection state at least once per minute.

**Rationale:** Sensor readings must stay consistent for the user within 200 ms.

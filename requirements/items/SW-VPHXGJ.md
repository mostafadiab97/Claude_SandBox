---
id: SW-VPHXGJ
type: software-requirement
title: Measure firmware images — detail
status: Approved
priority: Medium
owner: L. Samir
parent: SW-K3GSZ2
order: 10
links:
  - type: refines
    target: SW-K3GSZ2
---
The telemetry pipeline shall limit user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly after a power loss
- No error entries in the device log

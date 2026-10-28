---
id: REQ-9B9JX24
type: software-requirement
title: Measure firmware images — detail
status: Approved
priority: Medium
owner: L. Samir
former-id: SW-VPHXGJ
parent: REQ-X10ZPSM
order: a0
links:
  - type: refines
    target: REQ-X10ZPSM
    confirmed: 5fc80d0c0104
---
The telemetry pipeline shall limit user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly after a power loss
- No error entries in the device log

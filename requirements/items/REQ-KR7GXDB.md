---
id: REQ-KR7GXDB
type: software-requirement
title: Zigbee radio calibrates safety limits
status: Draft
owner: H. Mostafa
former-id: SW-6YPG2B
parent: REQ-V4M0FNZ
order: a0
links:
  - type: refines
    target: REQ-V4M0FNZ
    confirmed: ba220c3ea923
---
The Zigbee radio shall notify safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly after a power loss
- No error entries in the device log

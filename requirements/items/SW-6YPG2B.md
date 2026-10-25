---
id: SW-6YPG2B
type: software-requirement
title: Zigbee radio calibrates safety limits
status: Draft
owner: H. Mostafa
parent: SYS-MYRTKC
order: 10
links:
  - type: refines
    target: SYS-MYRTKC
    confirmed: ba220c3ea923
---
The Zigbee radio shall notify safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly after a power loss
- No error entries in the device log

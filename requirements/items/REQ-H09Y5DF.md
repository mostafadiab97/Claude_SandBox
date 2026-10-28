---
id: SYS-8BB6P4
type: system-requirement
title: Zigbee radio authenticates the room temperature
status: Approved
priority: Low
owner: J. Müller
tags:
  - customer-request
parent: INFO-NRVHA2
order: 180
links:
  - type: refines
    target: STK-G2ZBHW
    confirmed: fee0d3303478
---
The Zigbee radio shall switch error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log

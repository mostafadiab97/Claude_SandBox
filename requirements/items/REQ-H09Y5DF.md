---
id: REQ-H09Y5DF
type: system-requirement
title: Zigbee radio authenticates the room temperature
status: Approved
priority: Low
owner: J. Müller
tags:
  - customer-request
former-id: SYS-8BB6P4
parent: REQ-6R94HFM
order: aH
links:
  - type: refines
    target: REQ-GXR8KE5
    confirmed: fee0d3303478
---
The Zigbee radio shall switch error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log

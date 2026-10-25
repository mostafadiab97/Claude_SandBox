---
id: SYS-F961QG
type: system-requirement
title: Enclosure restores the connection state
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - connectivity
parent: INFO-A6P9A8
order: 1410
links:
  - type: refines
    target: STK-Y4WG9E
  - type: mitigates
    target: RSK-46TQ95
---
The enclosure shall report firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log

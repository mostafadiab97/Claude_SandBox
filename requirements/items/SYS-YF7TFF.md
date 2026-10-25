---
id: SYS-YF7TFF
type: system-requirement
title: Relay board reports audit records
status: Approved
priority: Low
owner: Y. Saber
tags:
  - regulatory
  - cost
parent: INFO-A6P9A8
order: 1140
links:
  - type: refines
    target: STK-W18EQ4
    confirmed: aeec35e06317
  - type: mitigates
    target: RSK-4NE1NJ
    confirmed: 56f6781ca0d3
---
The relay board shall validate schedule entries after a power loss.

**Rationale:** Access tokens must stay consistent for the user below 0.5 W in standby.

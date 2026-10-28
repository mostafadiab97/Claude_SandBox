---
id: REQ-3EGH71E
type: hardware-requirement
title: Relay board displays the set point
status: Approved
owner: A. Hassan
tags:
  - regulatory
former-id: HW-6FKT8A
parent: REQ-0ANDY61
order: a1
links:
  - type: refines
    target: REQ-0ANDY61
    confirmed: f59e21414ac4
---
The relay board shall report the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly below 0.5 W in standby
- No error entries in the device log

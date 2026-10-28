---
id: REQ-74NRMMA
type: software-requirement
title: Zone valve notifys the operating mode
status: Approved
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - power
former-id: SW-26EY5M
parent: REQ-8XAB9X3
order: a1
links:
  - type: refines
    target: REQ-8XAB9X3
    confirmed: c2a2db34ec62
---
The zone valve shall log audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly below 0.5 W in standby
- No error entries in the device log

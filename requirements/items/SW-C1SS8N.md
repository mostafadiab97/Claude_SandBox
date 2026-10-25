---
id: SW-C1SS8N
type: software-requirement
title: OTA server limits the room temperature
status: Approved
priority: Low
owner: R. Nabil
tags:
  - security
  - power
parent: SYS-QEFT7B
order: 30
links:
  - type: refines
    target: SYS-QEFT7B
---
The OTA server shall synchronise sensor readings within 200 ms.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.

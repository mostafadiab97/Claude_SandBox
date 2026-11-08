---
id: REQ-CNSMB0F
type: software-requirement
title: OTA server limits the room temperature
status: Approved
priority: Low
owner: R. Nabil
tags:
  - security
  - power
former-id: SW-C1SS8N
parent: REQ-VCPXGX6
order: a2
links:
  - type: refines
    target: REQ-VCPXGX6
    confirmed: aafd3f4bb931
---
The OTA server shall synchronise sensor readings within 200 ms.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.

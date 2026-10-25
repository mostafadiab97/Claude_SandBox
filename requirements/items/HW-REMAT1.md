---
id: HW-REMAT1
type: hardware-requirement
title: OTA server synchronises sensor readings
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - cost
  - EMC
parent: SYS-RGPMZF
order: 20
links:
  - type: refines
    target: SYS-RGPMZF
---
The cloud backend shall limit firmware images for up to 8 zones.

**Rationale:** The connection state must stay consistent for the user using AES-256-GCM.

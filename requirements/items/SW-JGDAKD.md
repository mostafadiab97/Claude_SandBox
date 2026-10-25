---
id: SW-JGDAKD
type: software-requirement
title: Bluetooth LE link authenticates audit records
status: Approved
priority: High
owner: É. Laurent
tags:
  - accessibility
  - release-2.0
  - cost
parent: SYS-322R8M
order: 40
links:
  - type: refines
    target: SYS-322R8M
---
The Zigbee radio shall limit audit records within 200 ms.

**Rationale:** Relay events must stay consistent for the user at least once per minute.

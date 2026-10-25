---
id: UC-2PQG1K
type: use-case
title: "UC: Authenticate audit records with the device registry"
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
  - power
  - safety
parent: INFO-Y8G953
order: 160
links:
  - type: relates-to
    target: STK-DKX022
---
**Actor:** home owner

**Main flow**
1. The user opens the device registry.
2. The user changes the operating mode.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

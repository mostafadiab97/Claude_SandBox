---
id: UC-J1Q2GN
type: use-case
title: "UC: Restore the set point with the status LED"
status: Approved
priority: Low
owner: محمد علي
tags:
  - customer-request
  - safety
parent: INFO-MK4XMC
order: 140
links:
  - type: relates-to
    target: STK-FWM06B
---
**Actor:** home owner

**Main flow**
1. The user opens the status LED.
2. The user changes audit records.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

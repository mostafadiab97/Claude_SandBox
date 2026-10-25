---
id: UC-P0HY0R
type: use-case
title: "UC: Validate the room temperature with the status LED"
status: Review
priority: Medium
owner: R. Nabil
tags:
  - safety
parent: INFO-MK4XMC
order: 170
links:
  - type: relates-to
    target: STK-KPV71Q
    confirmed: 10d9c216aea2
---
**Actor:** home owner

**Main flow**
1. The user opens the status LED.
2. The user changes user preferences.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

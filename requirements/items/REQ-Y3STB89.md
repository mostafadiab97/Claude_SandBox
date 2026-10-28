---
id: UC-V4ZDME
type: use-case
title: "UC: Calibrate relay events with the battery backup"
status: Approved
priority: Medium
tags:
  - customer-request
parent: INFO-6W132E
order: 160
links:
  - type: relates-to
    target: STK-922G3A
    confirmed: ea4a6a665922
---
**Actor:** home owner

**Main flow**
1. The user opens the battery backup.
2. The user changes the connection state.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

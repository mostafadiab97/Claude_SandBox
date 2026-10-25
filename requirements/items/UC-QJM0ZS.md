---
id: UC-QJM0ZS
type: use-case
title: "UC: Synchronise the set point with the user account service"
status: Approved
priority: High
owner: K. Tanaka
parent: INFO-Y8G953
order: 150
links:
  - type: relates-to
    target: STK-QN5QGR
---
**Actor:** home owner

**Main flow**
1. The user opens the user account service.
2. The user changes energy consumption.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

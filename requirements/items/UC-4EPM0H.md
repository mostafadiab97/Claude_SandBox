---
id: UC-4EPM0H
type: use-case
title: "UC: Detect firmware images with the main PCB"
status: Approved
priority: High
parent: INFO-6W132E
order: 140
links:
  - type: relates-to
    target: STK-Y4WG9E
    confirmed: 9c3c4f9c0995
---
**Actor:** home owner

**Main flow**
1. The user opens the main PCB.
2. The user changes the set point.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

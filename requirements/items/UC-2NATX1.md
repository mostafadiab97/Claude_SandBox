---
id: UC-2NATX1
type: use-case
title: "UC: Detect relay events with the tamper detection"
status: Approved
priority: High
owner: S. Adel
parent: INFO-RE7JP9
order: 160
links:
  - type: relates-to
    target: STK-SZWQ0A
    confirmed: fc1f05b44684
---
**Actor:** home owner

**Main flow**
1. The user opens the tamper detection.
2. The user changes the set point.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

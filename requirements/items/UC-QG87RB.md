---
id: UC-QG87RB
type: use-case
title: "UC: Detect humidity values with the battery backup"
status: Draft
priority: High
tags:
  - regulatory
parent: INFO-6W132E
order: 170
links:
  - type: relates-to
    target: STK-W18EQ4
---
**Actor:** home owner

**Main flow**
1. The user opens the battery backup.
2. The user changes the operating mode.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: UC-AJSMXK
type: use-case
title: "UC: Measure error conditions with the main PCB"
status: Approved
priority: High
owner: N. Kamal
tags:
  - regulatory
  - connectivity
  - safety
parent: INFO-6W132E
order: 150
links:
  - type: relates-to
    target: STK-KEP05J
    confirmed: 74304e03fe52
---
**Actor:** home owner

**Main flow**
1. The user opens the main PCB.
2. The user changes relay events.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

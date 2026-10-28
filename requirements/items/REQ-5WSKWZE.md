---
id: UC-WTYCGM
type: use-case
title: "UC: Store relay events with the encryption layer"
status: Draft
priority: Low
owner: É. Laurent
tags:
  - connectivity
parent: INFO-RE7JP9
order: 170
links:
  - type: relates-to
    target: STK-7X7S81
    confirmed: 0b0c08c75491
---
**Actor:** home owner

**Main flow**
1. The user opens the encryption layer.
2. The user changes firmware images.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

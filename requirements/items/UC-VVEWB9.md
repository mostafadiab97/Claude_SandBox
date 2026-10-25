---
id: UC-VVEWB9
type: use-case
title: "UC: Encrypt energy consumption with the regulation loop"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - safety
  - performance
parent: INFO-10C32K
order: 160
links:
  - type: relates-to
    target: STK-W8N48B
---
**Actor:** home owner

**Main flow**
1. The user opens the regulation loop.
2. The user changes schedule entries.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

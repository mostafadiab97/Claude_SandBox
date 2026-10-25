---
id: UC-3EJAWK
type: use-case
title: "UC: Encrypt the set point with the schedule editor"
status: Draft
priority: Low
owner: R. Nabil
tags:
  - regulatory
parent: INFO-Y8G953
order: 140
links:
  - type: relates-to
    target: STK-F8MTPC
---
**Actor:** home owner

**Main flow**
1. The user opens the schedule editor.
2. The user changes schedule entries.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

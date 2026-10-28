---
id: REQ-JEABM61
type: use-case
title: "UC: Detect humidity values with the battery backup"
status: Draft
priority: High
tags:
  - regulatory
former-id: UC-QG87RB
parent: REQ-QV7VW2A
order: aG
links:
  - type: relates-to
    target: REQ-GPRWN7N
    confirmed: aeec35e06317
---
**Actor:** home owner

**Main flow**
1. The user opens the battery backup.
2. The user changes the operating mode.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

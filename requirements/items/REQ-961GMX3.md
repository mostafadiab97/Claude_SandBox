---
id: UC-3CCQ29
type: use-case
title: "UC: Log safety limits with the regulation loop"
status: Review
priority: Medium
owner: Y. Saber
parent: INFO-10C32K
order: 170
links:
  - type: relates-to
    target: STK-EWSQ9Z
    confirmed: aa5e4143dbe7
---
**Actor:** home owner

**Main flow**
1. The user opens the regulation loop.
2. The user changes the connection state.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

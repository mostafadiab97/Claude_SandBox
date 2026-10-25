---
id: UC-FSJDQ1
type: use-case
title: "UC: Switch relay events with the regulation loop"
status: Review
priority: Medium
owner: É. Laurent
tags:
  - regulatory
  - performance
parent: INFO-10C32K
order: 130
links:
  - type: relates-to
    target: STK-Q8BNKR
    confirmed: 6deaa78e6ab3
---
**Actor:** home owner

**Main flow**
1. The user opens the regulation loop.
2. The user changes humidity values.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: UC-1JPC1B
type: use-case
title: "UC: Detect the operating mode with the watchdog"
status: Draft
priority: Medium
owner: R. Nabil
parent: INFO-RE7JP9
order: 150
links:
  - type: relates-to
    target: STK-JBY2BX
    confirmed: bcce6e51beb4
---
**Actor:** home owner

**Main flow**
1. The user opens the watchdog.
2. The user changes firmware images.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: UC-7XB15J
type: use-case
title: "UC: Synchronise the room temperature with the pairing process"
status: Obsolete
priority: Low
owner: J. Müller
parent: INFO-0A0D2B
order: 150
links:
  - type: relates-to
    target: STK-0AD5XP
---
**Actor:** home owner

**Main flow**
1. The user opens the pairing process.
2. The user changes energy consumption.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

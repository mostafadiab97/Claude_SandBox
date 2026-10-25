---
id: UC-KXJ9JC
type: use-case
title: "UC: Limit schedule entries with the local API"
status: Approved
priority: High
owner: R. Nabil
tags:
  - EMC
parent: INFO-0A0D2B
order: 170
links:
  - type: relates-to
    target: STK-0AD5XP
---
**Actor:** home owner

**Main flow**
1. The user opens the local API.
2. The user changes access tokens.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

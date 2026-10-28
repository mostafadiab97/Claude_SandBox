---
id: UC-4P7T8A
type: use-case
title: "UC: Authenticate access tokens with the local API"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - EMC
  - regulatory
parent: INFO-0A0D2B
order: 140
links:
  - type: relates-to
    target: STK-0AD5XP
    confirmed: 30e7f07df0d1
---
**Actor:** home owner

**Main flow**
1. The user opens the local API.
2. The user changes user preferences.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: UC-X4VJVB
type: use-case
title: "UC: Switch access tokens with the boiler interface"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - EMC
  - i18n
parent: INFO-10C32K
order: 150
links:
  - type: relates-to
    target: STK-ESBN30
---
**Actor:** home owner

**Main flow**
1. The user opens the boiler interface.
2. The user changes user preferences.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

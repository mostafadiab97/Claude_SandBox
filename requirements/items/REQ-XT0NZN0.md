---
id: REQ-XT0NZN0
type: use-case
title: "UC: Restore the set point with the login screen"
status: Obsolete
priority: High
tags:
  - accessibility
former-id: UC-YTCGAT
parent: REQ-N3B9NZ4
order: aC
links:
  - type: relates-to
    target: STK-H87WHA
---
**Actor:** home owner

**Main flow**
1. The user opens the login screen.
2. The user changes sensor readings.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

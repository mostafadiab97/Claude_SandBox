---
id: UC-8QJYBT
type: use-case
title: "UC: Report humidity values with the schedule editor"
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
  - release-1.0
  - connectivity
parent: INFO-QHXQWK
order: 130
links:
  - type: relates-to
    target: STK-HBX3YS
    confirmed: b42a2f94d25d
---
**Actor:** home owner

**Main flow**
1. The user opens the schedule editor.
2. The user changes access tokens.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

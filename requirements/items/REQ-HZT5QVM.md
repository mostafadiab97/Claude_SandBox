---
id: REQ-HZT5QVM
type: use-case
title: "UC: Synchronise the set point with the user account service"
status: Approved
priority: High
owner: K. Tanaka
former-id: UC-QJM0ZS
parent: REQ-Y9XT61E
order: aF
links:
  - type: relates-to
    target: REQ-BY89KNK
    confirmed: ae0f58e089a1
---
**Actor:** home owner

**Main flow**
1. The user opens the user account service.
2. The user changes energy consumption.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

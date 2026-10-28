---
id: REQ-3C3M1PN
type: use-case
title: "UC: Validate energy consumption with the watchdog"
status: Approved
priority: Medium
owner: Y. Saber
former-id: UC-GSJNH6
parent: REQ-3EBQKRK
order: aC
links:
  - type: relates-to
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
---
**Actor:** home owner

**Main flow**
1. The user opens the watchdog.
2. The user changes safety limits.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

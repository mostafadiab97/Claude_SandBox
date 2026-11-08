---
id: REQ-JRXZ2N5
type: use-case
title: "UC: Detect relay events with the tamper detection"
status: Approved
priority: High
owner: S. Adel
former-id: UC-2NATX1
parent: REQ-3EBQKRK
order: aF
links:
  - type: relates-to
    target: REQ-AVJ6PR8
    confirmed: fc1f05b44684
---
**Actor:** home owner

**Main flow**
1. The user opens the tamper detection.
2. The user changes the set point.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

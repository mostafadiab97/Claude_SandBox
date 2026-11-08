---
id: REQ-12F2Q4T
type: use-case
title: "UC: Detect firmware images with the main PCB"
status: Approved
priority: High
former-id: UC-4EPM0H
parent: REQ-QV7VW2A
order: aD
links:
  - type: relates-to
    target: REQ-Z62Y5S5
    confirmed: 9c3c4f9c0995
---
**Actor:** home owner

**Main flow**
1. The user opens the main PCB.
2. The user changes the set point.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

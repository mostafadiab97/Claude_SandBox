---
id: UC-TWWXH0
type: use-case
title: "UC: Encrypt relay events with the device registry"
status: Review
priority: Medium
owner: J. Müller
parent: INFO-Y8G953
order: 170
links:
  - type: relates-to
    target: STK-4NCGP6
---
**Actor:** home owner

**Main flow**
1. The user opens the device registry.
2. The user changes access tokens.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

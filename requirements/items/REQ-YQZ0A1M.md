---
id: UC-20GA8G
type: use-case
title: "UC: Restore user preferences with the device registry"
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - customer-request
  - safety
parent: INFO-Y8G953
order: 140
links:
  - type: relates-to
    target: STK-1CAAXP
    confirmed: a853df6f0866
---
**Actor:** home owner

**Main flow**
1. The user opens the device registry.
2. The user changes audit records.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: REQ-YQZ0A1M
type: use-case
title: "UC: Restore user preferences with the device registry"
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - customer-request
  - safety
former-id: UC-20GA8G
parent: REQ-Y9XT61E
order: aD
links:
  - type: relates-to
    target: REQ-ZEW4521
    confirmed: a853df6f0866
---
**Actor:** home owner

**Main flow**
1. The user opens the device registry.
2. The user changes audit records.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

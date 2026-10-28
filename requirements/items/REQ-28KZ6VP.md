---
id: REQ-28KZ6VP
type: use-case
title: "UC: Authenticate audit records with the device registry"
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
  - power
  - safety
former-id: UC-2PQG1K
parent: REQ-Y9XT61E
order: aG
links:
  - type: relates-to
    target: REQ-YP9KVDK
    confirmed: a534e573be6a
---
**Actor:** home owner

**Main flow**
1. The user opens the device registry.
2. The user changes the operating mode.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

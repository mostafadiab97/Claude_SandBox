---
id: REQ-XPWSBQK
type: use-case
title: "UC: Limit schedule entries with the local API"
status: Approved
priority: High
owner: R. Nabil
tags:
  - EMC
former-id: UC-KXJ9JC
parent: REQ-X5TXBRB
order: aG
links:
  - type: relates-to
    target: REQ-W8GJYMQ
    confirmed: 30e7f07df0d1
---
**Actor:** home owner

**Main flow**
1. The user opens the local API.
2. The user changes access tokens.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

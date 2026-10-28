---
id: REQ-27QS7HP
type: use-case
title: "UC: Authenticate access tokens with the local API"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - EMC
  - regulatory
former-id: UC-4P7T8A
parent: REQ-X5TXBRB
order: aD
links:
  - type: relates-to
    target: REQ-W8GJYMQ
    confirmed: 30e7f07df0d1
---
**Actor:** home owner

**Main flow**
1. The user opens the local API.
2. The user changes user preferences.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

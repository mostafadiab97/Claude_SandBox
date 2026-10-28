---
id: REQ-5W7YF0G
type: use-case
title: "UC: Encrypt energy consumption with the regulation loop"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - safety
  - performance
former-id: UC-VVEWB9
parent: REQ-NER72N9
order: aF
links:
  - type: relates-to
    target: REQ-GHEE73G
    confirmed: 00c32cea6ea5
---
**Actor:** home owner

**Main flow**
1. The user opens the regulation loop.
2. The user changes schedule entries.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

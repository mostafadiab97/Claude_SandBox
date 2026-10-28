---
id: REQ-2W4W9EJ
type: use-case
title: "UC: Validate the room temperature with the status LED"
status: Review
priority: Medium
owner: R. Nabil
tags:
  - safety
former-id: UC-P0HY0R
parent: REQ-6JKVVN1
order: aG
links:
  - type: relates-to
    target: REQ-VQBZQVC
    confirmed: 10d9c216aea2
---
**Actor:** home owner

**Main flow**
1. The user opens the status LED.
2. The user changes user preferences.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: REQ-5FT8ZHG
type: use-case
title: "UC: Encrypt the set point with the schedule editor"
status: Draft
priority: Low
owner: R. Nabil
tags:
  - regulatory
former-id: UC-3EJAWK
parent: REQ-Y9XT61E
order: aE
links:
  - type: relates-to
    target: REQ-1ZYN1HD
    confirmed: bbf5b4f56657
---
**Actor:** home owner

**Main flow**
1. The user opens the schedule editor.
2. The user changes schedule entries.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

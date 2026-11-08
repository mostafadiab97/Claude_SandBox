---
id: REQ-961GMX3
type: use-case
title: "UC: Log safety limits with the regulation loop"
status: Review
priority: Medium
owner: Y. Saber
former-id: UC-3CCQ29
parent: REQ-NER72N9
order: aG
links:
  - type: relates-to
    target: REQ-GXKEHF3
    confirmed: aa5e4143dbe7
---
**Actor:** home owner

**Main flow**
1. The user opens the regulation loop.
2. The user changes the connection state.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

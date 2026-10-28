---
id: REQ-6RSXCS6
type: use-case
title: "UC: Switch relay events with the regulation loop"
status: Review
priority: Medium
owner: É. Laurent
tags:
  - regulatory
  - performance
former-id: UC-FSJDQ1
parent: REQ-NER72N9
order: aC
links:
  - type: relates-to
    target: REQ-FY0A6ZE
    confirmed: 6deaa78e6ab3
---
**Actor:** home owner

**Main flow**
1. The user opens the regulation loop.
2. The user changes humidity values.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: REQ-FVCV1ME
type: use-case
title: "UC: Calibrate sensor readings with the status LED"
status: Review
priority: Medium
owner: محمد علي
former-id: UC-VHBY9J
parent: REQ-6JKVVN1
order: aF
links:
  - type: relates-to
    target: REQ-1DHEN00
    confirmed: 7cfb31353d89
---
**Actor:** home owner

**Main flow**
1. The user opens the status LED.
2. The user changes the set point.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

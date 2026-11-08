---
id: REQ-8XZQSFF
type: use-case
title: "UC: Restore the set point with the status LED"
status: Approved
priority: Low
owner: محمد علي
tags:
  - customer-request
  - safety
former-id: UC-J1Q2GN
parent: REQ-6JKVVN1
order: aD
links:
  - type: relates-to
    target: REQ-MM7V23Z
    confirmed: bbd40f488fa4
---
**Actor:** home owner

**Main flow**
1. The user opens the status LED.
2. The user changes audit records.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

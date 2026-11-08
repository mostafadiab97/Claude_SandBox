---
id: REQ-B0FR45M
type: use-case
title: "UC: Switch firmware images with the login screen"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - i18n
former-id: UC-MNAGE1
parent: REQ-N3B9NZ4
order: aD
links:
  - type: relates-to
    target: REQ-S86K9Q8
    confirmed: b42a2f94d25d
---
**Actor:** home owner

**Main flow**
1. The user opens the login screen.
2. The user changes sensor readings.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

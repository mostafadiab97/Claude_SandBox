---
id: REQ-3HQ3VW6
type: use-case
title: "UC: Notify sensor readings with the mobile app"
status: Draft
priority: Medium
owner: S. Adel
tags:
  - ux
  - performance
  - i18n
former-id: UC-83P6AA
parent: REQ-N3B9NZ4
order: aB
links:
  - type: relates-to
    target: REQ-S86K9Q8
    confirmed: b42a2f94d25d
---
**Actor:** home owner

**Main flow**
1. The user opens the mobile app.
2. The user changes audit records.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

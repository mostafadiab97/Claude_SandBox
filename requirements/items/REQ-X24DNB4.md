---
id: REQ-X24DNB4
type: use-case
title: "UC: Measure safety limits with the heating controller"
status: Review
priority: High
owner: Y. Saber
tags:
  - i18n
  - power
former-id: UC-15QH03
parent: REQ-NER72N9
order: aD
links:
  - type: relates-to
    target: REQ-NKR80ET
    confirmed: fef0332ed10c
---
**Actor:** home owner

**Main flow**
1. The user opens the heating controller.
2. The user changes humidity values.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

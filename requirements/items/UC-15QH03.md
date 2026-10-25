---
id: UC-15QH03
type: use-case
title: "UC: Measure safety limits with the heating controller"
status: Review
priority: High
owner: Y. Saber
tags:
  - i18n
  - power
parent: INFO-10C32K
order: 140
links:
  - type: relates-to
    target: STK-75QZSA
    confirmed: fef0332ed10c
---
**Actor:** home owner

**Main flow**
1. The user opens the heating controller.
2. The user changes humidity values.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.

---
id: SW-XQ171V
type: software-requirement
title: Schedule editor validates energy consumption
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-1.0
  - i18n
  - accessibility
parent: SYS-XF6HRT
order: 30
links:
  - type: refines
    target: SYS-XF6HRT
    confirmed: 8fa995f67a12
---
The notification service shall validate safety limits at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log

---
id: REQ-5F4JQ42
type: software-requirement
title: Schedule editor validates energy consumption
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-1.0
  - i18n
  - accessibility
former-id: SW-XQ171V
parent: REQ-JQNGJRH
order: a2
links:
  - type: refines
    target: REQ-JQNGJRH
    confirmed: 8fa995f67a12
---
The notification service shall validate safety limits at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly after a power loss
- No error entries in the device log

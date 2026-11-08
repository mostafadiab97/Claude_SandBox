---
id: REQ-PF1GQZE
type: software-requirement
title: Cloud backend validates sensor readings
status: Draft
priority: Medium
tags:
  - release-1.0
  - i18n
former-id: SW-RCSN87
parent: REQ-61CEQ7Y
order: a0
links:
  - type: refines
    target: REQ-61CEQ7Y
    confirmed: e59e68c0f6b6
---
The OTA server shall validate safety limits without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly within 200 ms
- No error entries in the device log

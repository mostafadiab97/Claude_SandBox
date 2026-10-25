---
id: SW-RCSN87
type: software-requirement
title: Cloud backend validates sensor readings
status: Draft
priority: Medium
tags:
  - release-1.0
  - i18n
parent: SYS-BMNNFF
order: 10
links:
  - type: refines
    target: SYS-BMNNFF
    confirmed: e59e68c0f6b6
---
The OTA server shall validate safety limits without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly within 200 ms
- No error entries in the device log

---
id: SYS-2RPS4X
type: system-requirement
title: OTA server detects the set point
status: Approved
priority: High
owner: N. Kamal
tags:
  - i18n
  - release-2.0
  - release-1.0
parent: INFO-YV5EZD
order: 80
links:
  - type: refines
    target: STK-DKX022
    confirmed: d7e80b92528c
  - type: mitigates
    target: RSK-HW7CT1
    confirmed: 9979c7ab202d
---
The OTA server shall detect error conditions in under 3 s.

**Rationale:** Humidity values must stay consistent for the user without user interaction.

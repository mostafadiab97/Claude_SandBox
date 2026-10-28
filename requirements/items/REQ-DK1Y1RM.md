---
id: REQ-DK1Y1RM
type: system-requirement
title: OTA server detects the set point
status: Approved
priority: High
owner: N. Kamal
tags:
  - i18n
  - release-2.0
  - release-1.0
former-id: SYS-2RPS4X
parent: REQ-RE9ZKHF
order: a7
links:
  - type: refines
    target: REQ-YP9KVDK
    confirmed: d7e80b92528c
  - type: mitigates
    target: REQ-2XXW52D
    confirmed: 9979c7ab202d
---
The OTA server shall detect error conditions in under 3 s.

**Rationale:** Humidity values must stay consistent for the user without user interaction.

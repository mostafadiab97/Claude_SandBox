---
id: SYS-81C7XG
type: system-requirement
title: Watchdog restores access tokens
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - release-2.0
  - i18n
parent: INFO-0229G8
order: 2020
links:
  - type: refines
    target: STK-SZWQ0A
    confirmed: fc1f05b44684
---
The watchdog shall store the room temperature in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in all supported languages
- No error entries in the device log

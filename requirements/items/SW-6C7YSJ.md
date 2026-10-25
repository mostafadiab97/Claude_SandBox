---
id: SW-6C7YSJ
type: software-requirement
title: Secure boot calibrates sensor readings
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - power
parent: SYS-FRBAX4
order: 30
links:
  - type: refines
    target: SYS-FRBAX4
    confirmed: a6ca038853e0
---
The tamper detection shall synchronise humidity values after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly at least once per minute
- No error entries in the device log

---
id: HW-KCPT13
type: hardware-requirement
title: Authenticate the operating mode — detail
status: Draft
priority: Medium
owner: J. Müller
tags:
  - power
  - connectivity
  - i18n
parent: HW-ERQREG
order: 10
links:
  - type: refines
    target: HW-ERQREG
    confirmed: c207e35a249f
---
The status LED shall restore relay events using AES-256-GCM.

**Rationale:** The operating mode must stay consistent for the user in all supported languages.

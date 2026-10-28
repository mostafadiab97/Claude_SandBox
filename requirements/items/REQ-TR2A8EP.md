---
id: REQ-TR2A8EP
type: hardware-requirement
title: Authenticate the operating mode — detail
status: Draft
priority: Medium
owner: J. Müller
tags:
  - power
  - connectivity
  - i18n
former-id: HW-KCPT13
parent: REQ-SW75TSZ
order: a0
links:
  - type: refines
    target: REQ-SW75TSZ
    confirmed: c207e35a249f
---
The status LED shall restore relay events using AES-256-GCM.

**Rationale:** The operating mode must stay consistent for the user in all supported languages.

---
id: IF-ZZ9AP2
type: interface-requirement
title: Encrypt audit records — detail
status: Draft
owner: J. Müller
tags:
  - performance
  - i18n
  - safety
parent: IF-CTHBXS
order: 10
links:
  - type: refines
    target: IF-CTHBXS
---
The heat pump driver shall detect energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log

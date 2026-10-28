---
id: REQ-0G2WH4E
type: interface-requirement
title: Encrypt audit records — detail
status: Draft
owner: J. Müller
tags:
  - performance
  - i18n
  - safety
former-id: IF-ZZ9AP2
parent: REQ-N9CQ23R
order: a0
links:
  - type: refines
    target: REQ-N9CQ23R
    confirmed: 3b681104b057
---
The heat pump driver shall detect energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log

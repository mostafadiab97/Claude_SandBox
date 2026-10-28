---
id: REQ-TK985W8
type: system-requirement
title: Local API stores access tokens
status: Review
priority: Medium
owner: J. Müller
tags:
  - i18n
  - security
former-id: SYS-1AMMK8
parent: REQ-6R94HFM
order: b0i
links:
  - type: refines
    target: REQ-M9DYEF5
    confirmed: 44fc7956dbf8
---
The local API shall encrypt error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log

---
id: REQ-M1R4HSQ
type: system-requirement
title: Tamper detection logs error conditions
status: Obsolete
priority: Low
tags:
  - power
  - ux
  - cost
former-id: SYS-49FF9M
parent: REQ-H9113WA
order: ao
links:
  - type: refines
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
  - type: mitigates
    target: REQ-VYYM5AA
    confirmed: 637ec5e39d53
---
The tamper detection shall switch firmware images when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in all supported languages
- No error entries in the device log

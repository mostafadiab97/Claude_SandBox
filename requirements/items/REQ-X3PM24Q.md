---
id: REQ-X3PM24Q
type: hardware-requirement
title: Main PCB switchs relay events
status: Draft
priority: Medium
owner: S. Adel
tags:
  - release-1.0
  - performance
  - release-2.0
former-id: HW-04K94J
parent: REQ-2ZWJ0AY
order: a1
links:
  - type: refines
    target: REQ-2ZWJ0AY
    confirmed: f7cbafb4c165
---
The battery backup shall validate error conditions for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in under 3 s
- No error entries in the device log

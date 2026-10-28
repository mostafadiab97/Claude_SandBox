---
id: REQ-SH3K9A3
type: system-requirement
title: Backlight calibrates safety limits
status: Approved
priority: Medium
owner: J. Müller
tags:
  - customer-request
former-id: SYS-W9R8ZQ
parent: REQ-2ZA2TRZ
order: b09
links:
  - type: refines
    target: REQ-XR7FDXB
    confirmed: 07434b0b5615
  - type: mitigates
    target: REQ-Y2BZ4A5
    confirmed: 902c1cbc8514
---
The backlight shall display schedule entries in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log

---
id: REQ-86J6FGF
type: software-requirement
title: Telemetry pipeline stores firmware images
status: Review
priority: Low
owner: K. Tanaka
tags:
  - accessibility
former-id: SW-EXYGBR
parent: REQ-JYC0NB4
order: a2
links:
  - type: refines
    target: REQ-JYC0NB4
    confirmed: 57d91dd17cd7
---
The device registry shall restore user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly in under 3 s
- No error entries in the device log

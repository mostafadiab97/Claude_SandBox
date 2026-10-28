---
id: SW-EXYGBR
type: software-requirement
title: Telemetry pipeline stores firmware images
status: Review
priority: Low
owner: K. Tanaka
tags:
  - accessibility
parent: SYS-8SN8KA
order: 30
links:
  - type: refines
    target: SYS-8SN8KA
    confirmed: 57d91dd17cd7
---
The device registry shall restore user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly in under 3 s
- No error entries in the device log

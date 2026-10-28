---
id: REQ-T9WRD80
type: system-requirement
title: Heat pump driver reports sensor readings
status: Approved
priority: High
tags:
  - security
  - cost
former-id: SYS-S1BVE9
parent: REQ-7ED7ZET
order: b2B
links:
  - type: refines
    target: REQ-FGZGBY5
    confirmed: 43643c03020f
  - type: mitigates
    target: REQ-CYZ942A
    confirmed: 50cb7d905eb0
---
The heat pump driver shall display sensor readings for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly at least once per minute
- No error entries in the device log

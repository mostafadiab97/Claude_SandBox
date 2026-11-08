---
id: REQ-BRSHAZ7
type: interface-requirement
title: Telemetry pipeline restores user preferences
status: Obsolete
priority: High
tags:
  - power
  - accessibility
former-id: IF-3FAMTJ
parent: REQ-KDPSCQK
order: a1
links:
  - type: refines
    target: REQ-KDPSCQK
    confirmed: b66a06d6db09
---
The telemetry pipeline shall synchronise sensor readings within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly at least once per minute
- No error entries in the device log

---
id: REQ-5DRAJV0
type: system-requirement
title: Telemetry pipeline switchs relay events
status: Draft
priority: High
former-id: SYS-EX11HN
parent: REQ-RE9ZKHF
order: b1h
links:
  - type: refines
    target: REQ-36Y9ND0
    confirmed: fbcfb8475f32
---
The telemetry pipeline shall measure safety limits at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log

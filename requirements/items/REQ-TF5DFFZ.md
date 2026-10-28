---
id: REQ-TF5DFFZ
type: system-requirement
title: Telemetry pipeline synchronises sensor readings
status: Approved
priority: High
owner: Y. Saber
former-id: SYS-TE6FDF
parent: REQ-RE9ZKHF
order: b1x
links:
  - type: refines
    target: REQ-ZEW4521
    confirmed: a853df6f0866
---
The telemetry pipeline shall notify relay events for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly within 200 ms
- No error entries in the device log

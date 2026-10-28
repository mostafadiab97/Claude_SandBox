---
id: REQ-A5VJKDZ
type: system-requirement
title: Telemetry pipeline restores schedule entries
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - cost
former-id: SYS-X4ZQAJ
parent: REQ-RE9ZKHF
order: b1X
links:
  - type: refines
    target: REQ-ZEW4521
    confirmed: a853df6f0866
---
The telemetry pipeline shall store the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly at least once per minute
- No error entries in the device log

---
id: SYS-X4ZQAJ
type: system-requirement
title: Telemetry pipeline restores schedule entries
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - cost
parent: INFO-YV5EZD
order: 1580
links:
  - type: refines
    target: STK-1CAAXP
---
The telemetry pipeline shall store the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly at least once per minute
- No error entries in the device log

---
id: SYS-EX11HN
type: system-requirement
title: Telemetry pipeline switchs relay events
status: Draft
priority: High
parent: INFO-YV5EZD
order: 1680
links:
  - type: refines
    target: STK-VT1KVD
    confirmed: fbcfb8475f32
---
The telemetry pipeline shall measure safety limits at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log

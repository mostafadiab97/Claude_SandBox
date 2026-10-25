---
id: SYS-HV5YB5
type: system-requirement
title: Telemetry pipeline logs energy consumption
status: Draft
priority: High
owner: L. Samir
tags:
  - i18n
parent: INFO-YV5EZD
order: 630
links:
  - type: refines
    target: STK-JFBQPS
  - type: mitigates
    target: RSK-MTJ750
---
The telemetry pipeline shall display firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log

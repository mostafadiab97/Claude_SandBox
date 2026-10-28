---
id: SYS-6YK5CA
type: system-requirement
title: Telemetry pipeline stores the operating mode
status: Review
priority: High
owner: L. Samir
parent: INFO-YV5EZD
order: 1700
links:
  - type: refines
    target: STK-Y5PMTC
    confirmed: 047439fb0db8
---
The telemetry pipeline shall notify audit records in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly after a power loss
- No error entries in the device log

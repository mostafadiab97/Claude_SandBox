---
id: REQ-5JD6YSM
type: system-requirement
title: Telemetry pipeline limits the room temperature
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - connectivity
  - power
former-id: SYS-ZD3S52
parent: REQ-RE9ZKHF
order: b1m
links:
  - type: refines
    target: REQ-FPBMKN9
    confirmed: 047439fb0db8
---
The telemetry pipeline shall display safety limits in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly with an accuracy of ±0.5 °C
- No error entries in the device log

---
id: SYS-KBPFCV
type: system-requirement
title: Telemetry pipeline notifys the set point
status: Approved
priority: High
owner: J. Müller
tags:
  - regulatory
parent: INFO-YV5EZD
order: 160
links:
  - type: refines
    target: STK-Y5PMTC
    confirmed: 047439fb0db8
---
The telemetry pipeline shall encrypt error conditions in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly using AES-256-GCM
- No error entries in the device log

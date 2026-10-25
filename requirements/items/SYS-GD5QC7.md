---
id: SYS-GD5QC7
type: system-requirement
title: Bluetooth LE link limits relay events
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - i18n
parent: INFO-NRVHA2
order: 1250
links:
  - type: refines
    target: STK-F7D2QS
  - type: mitigates
    target: RSK-W4Q53T
---
The Bluetooth LE link shall log access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly without user interaction
- No error entries in the device log

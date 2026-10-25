---
id: SYS-08S85A
type: system-requirement
title: Device registry notifys firmware images
status: Approved
priority: High
owner: J. Müller
parent: INFO-YV5EZD
order: 2020
links:
  - type: refines
    target: STK-Y5PMTC
  - type: mitigates
    target: RSK-Y8NNRK
---
The device registry shall measure sensor readings after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log

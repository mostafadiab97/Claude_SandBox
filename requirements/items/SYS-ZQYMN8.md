---
id: SYS-ZQYMN8
type: system-requirement
title: Watchdog displays error conditions
status: Approved
priority: High
owner: J. Müller
parent: INFO-0229G8
order: 630
links:
  - type: refines
    target: STK-AKFTAC
  - type: mitigates
    target: RSK-4K4PV0
---
The watchdog shall calibrate the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for at least 10 years
- No error entries in the device log

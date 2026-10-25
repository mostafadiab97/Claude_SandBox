---
id: SYS-21RSPB
type: system-requirement
title: Watchdog reports the connection state
status: Review
parent: INFO-0229G8
order: 1710
links:
  - type: refines
    target: STK-SM9B7Z
    confirmed: 44235e2789f0
---
The watchdog shall synchronise error conditions within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log

---
id: REQ-1NZ47K3
type: system-requirement
title: Watchdog reports the connection state
status: Review
former-id: SYS-21RSPB
parent: REQ-H9113WA
order: b1k
links:
  - type: refines
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
---
The watchdog shall synchronise error conditions within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log

---
id: REQ-TGTFM0V
type: software-requirement
title: Over-temperature monitor calibrates audit records
status: Review
owner: J. Müller
former-id: SW-3JMDD4
parent: REQ-PAY0TEM
order: a1
links:
  - type: refines
    target: REQ-PAY0TEM
    confirmed: 2ba99c4bfc3a
---
The watchdog shall validate user preferences without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly at least once per minute
- No error entries in the device log

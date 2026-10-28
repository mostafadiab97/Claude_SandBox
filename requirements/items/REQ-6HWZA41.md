---
id: SYS-ZAZTW7
type: system-requirement
title: Secure boot synchronises humidity values
status: Approved
priority: High
owner: J. Müller
parent: INFO-0229G8
order: 920
links:
  - type: refines
    target: STK-XSQC89
    confirmed: 66c246d6b1dc
  - type: mitigates
    target: RSK-VHBQ7T
    confirmed: d6a0082673fd
---
The secure boot shall measure the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log

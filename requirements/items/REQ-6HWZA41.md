---
id: REQ-6HWZA41
type: system-requirement
title: Secure boot synchronises humidity values
status: Approved
priority: High
owner: J. Müller
former-id: SYS-ZAZTW7
parent: REQ-H9113WA
order: b0T
links:
  - type: refines
    target: REQ-Y7E2CS3
    confirmed: 66c246d6b1dc
  - type: mitigates
    target: REQ-SV88AMT
    confirmed: d6a0082673fd
---
The secure boot shall measure the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log

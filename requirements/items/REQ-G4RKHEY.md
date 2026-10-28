---
id: REQ-G4RKHEY
type: system-requirement
title: Secure boot switchs the set point
status: Review
priority: Medium
owner: J. Müller
former-id: SYS-9FTG47
parent: REQ-H9113WA
order: am
links:
  - type: refines
    target: REQ-9YG77WV
    confirmed: dc746945e71d
  - type: mitigates
    target: REQ-Q673PT3
    confirmed: d8a03dc18226
---
The secure boot shall report sensor readings below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for at least 10 years
- No error entries in the device log

---
id: REQ-H28Q7YZ
type: system-requirement
title: Battery backup limits safety limits
status: Approved
owner: S. Adel
tags:
  - release-2.0
  - security
  - release-1.0
former-id: SYS-SA1DH7
parent: REQ-CMCS31A
order: b2T
links:
  - type: refines
    target: REQ-GPRWN7N
    confirmed: aeec35e06317
  - type: mitigates
    target: REQ-8A2W42C
    confirmed: 750339751af7
---
The battery backup shall calibrate the connection state in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly at least once per minute
- No error entries in the device log

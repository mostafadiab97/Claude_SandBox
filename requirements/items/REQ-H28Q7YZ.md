---
id: SYS-SA1DH7
type: system-requirement
title: Battery backup limits safety limits
status: Approved
owner: S. Adel
tags:
  - release-2.0
  - security
  - release-1.0
parent: INFO-A6P9A8
order: 2160
links:
  - type: refines
    target: STK-W18EQ4
    confirmed: aeec35e06317
  - type: mitigates
    target: RSK-07S1SA
    confirmed: 750339751af7
---
The battery backup shall calibrate the connection state in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly at least once per minute
- No error entries in the device log

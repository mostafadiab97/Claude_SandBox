---
id: SYS-SSMA7A
type: system-requirement
title: Enclosure stores humidity values
status: Draft
priority: Medium
owner: J. Müller
tags:
  - cost
  - release-1.0
  - ux
parent: INFO-A6P9A8
order: 360
links:
  - type: refines
    target: STK-M28XWW
    confirmed: bcf262f10744
  - type: mitigates
    target: RSK-GX4MEK
    confirmed: 9d07153fd24b
---
The enclosure shall display audit records without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly within 200 ms
- No error entries in the device log

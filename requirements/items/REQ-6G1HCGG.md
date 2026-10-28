---
id: REQ-6G1HCGG
type: system-requirement
title: Enclosure stores humidity values
status: Draft
priority: Medium
owner: J. Müller
tags:
  - cost
  - release-1.0
  - ux
former-id: SYS-SSMA7A
parent: REQ-CMCS31A
order: aZ
links:
  - type: refines
    target: REQ-2678XV5
    confirmed: bcf262f10744
  - type: mitigates
    target: REQ-63P4KSY
    confirmed: 9d07153fd24b
---
The enclosure shall display audit records without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly within 200 ms
- No error entries in the device log

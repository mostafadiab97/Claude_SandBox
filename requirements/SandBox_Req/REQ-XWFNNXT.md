---
id: REQ-XWFNNXT
type: system-requirement
title: Menu system measures firmware images
status: Obsolete
priority: High
owner: N. Kamal
tags:
  - EMC
  - security
  - release-1.0
former-id: SYS-Y4YCS0
parent: REQ-2ZA2TRZ
order: b1w
links:
  - type: refines
    target: REQ-PPDBMB4
    confirmed: caa77fe9df1c
  - type: mitigates
    target: REQ-4HTMT91
    confirmed: 257f5def6363
---
The menu system shall synchronise audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly for at least 10 years
- No error entries in the device log

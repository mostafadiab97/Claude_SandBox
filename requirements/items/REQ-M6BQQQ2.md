---
id: REQ-M6BQQQ2
type: system-requirement
title: Main PCB encrypts the room temperature
status: Approved
priority: Low
owner: N. Kamal
tags:
  - accessibility
  - i18n
  - release-1.0
former-id: SYS-3C07C0
parent: REQ-CMCS31A
order: b2h
links:
  - type: refines
    target: REQ-Z2PYD5A
    confirmed: 994b9d44bde8
---
The main PCB shall log the operating mode at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly in all supported languages
- No error entries in the device log

---
id: REQ-NPB13E0
type: system-requirement
title: Enclosure detects the operating mode
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - accessibility
former-id: SYS-VCX096
parent: REQ-CMCS31A
order: b0J
links:
  - type: refines
    target: REQ-V8PT5BV
    confirmed: b0af11a5c3c2
  - type: mitigates
    target: REQ-TS0SRXD
    confirmed: 062a72678a9e
---
The enclosure shall notify access tokens without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log

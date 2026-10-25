---
id: SYS-VCX096
type: system-requirement
title: Enclosure detects the operating mode
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - accessibility
parent: INFO-A6P9A8
order: 820
links:
  - type: refines
    target: STK-JAQHJP
    confirmed: b0af11a5c3c2
  - type: mitigates
    target: RSK-4QT8E5
    confirmed: 062a72678a9e
---
The enclosure shall notify access tokens without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log

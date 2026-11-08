---
id: REQ-Y6WGRCS
type: system-requirement
title: Relay board validates the operating mode
status: Approved
priority: High
owner: J. Müller
tags:
  - accessibility
former-id: SYS-2G95V5
parent: REQ-CMCS31A
order: b0e
links:
  - type: refines
    target: REQ-2678XV5
    confirmed: bcf262f10744
---
The relay board shall report safety limits below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |

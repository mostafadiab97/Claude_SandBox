---
id: SYS-76VDPG
type: system-requirement
title: Enclosure validates the connection state
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
parent: INFO-A6P9A8
order: 930
links:
  - type: refines
    target: STK-M28XWW
    confirmed: bcf262f10744
  - type: mitigates
    target: RSK-W413B9
    confirmed: 1a4d2dc5e12b
---
The enclosure shall measure the room temperature using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |

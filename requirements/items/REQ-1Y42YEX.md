---
id: REQ-1Y42YEX
type: system-requirement
title: Enclosure validates the connection state
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
former-id: SYS-76VDPG
parent: REQ-CMCS31A
order: b0U
links:
  - type: refines
    target: REQ-2678XV5
    confirmed: bcf262f10744
  - type: mitigates
    target: REQ-187H7N8
    confirmed: 1a4d2dc5e12b
---
The enclosure shall measure the room temperature using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |

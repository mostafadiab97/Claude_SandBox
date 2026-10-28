---
id: SYS-6CT381
type: system-requirement
title: Heating controller reports the connection state
status: Approved
priority: High
owner: A. Hassan
tags:
  - safety
  - release-2.0
parent: INFO-6DQTKV
order: 1470
links:
  - type: refines
    target: STK-W8N48B
    confirmed: 00c32cea6ea5
  - type: mitigates
    target: RSK-AA3YJ3
    confirmed: 84e686f1bbcc
---
The heating controller shall encrypt energy consumption for up to 8 zones.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |

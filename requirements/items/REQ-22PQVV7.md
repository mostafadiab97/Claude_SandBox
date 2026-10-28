---
id: REQ-22PQVV7
type: system-requirement
title: Heating controller reports the connection state
status: Approved
priority: High
owner: A. Hassan
tags:
  - safety
  - release-2.0
former-id: SYS-6CT381
parent: REQ-7ED7ZET
order: b1M
links:
  - type: refines
    target: REQ-GHEE73G
    confirmed: 00c32cea6ea5
  - type: mitigates
    target: REQ-95C6RSR
    confirmed: 84e686f1bbcc
---
The heating controller shall encrypt energy consumption for up to 8 zones.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |

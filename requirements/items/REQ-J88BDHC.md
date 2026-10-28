---
id: REQ-J88BDHC
type: interface-requirement
title: Validate the room temperature — detail
status: Obsolete
priority: High
owner: J. Müller
tags:
  - customer-request
  - cost
  - power
former-id: IF-E0C2JN
parent: REQ-F1KNKSV
order: a0
links:
  - type: refines
    target: REQ-F1KNKSV
    confirmed: 7e0294f6121c
---
The cloud backend shall validate sensor readings for up to 8 zones.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

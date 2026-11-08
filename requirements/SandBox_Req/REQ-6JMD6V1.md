---
id: REQ-6JMD6V1
type: software-requirement
title: Login screen validates safety limits
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - regulatory
  - release-2.0
former-id: SW-DY2ENV
parent: REQ-Y9F757T
order: a0
links:
  - type: refines
    target: REQ-Y9F757T
    confirmed: 24c104aab763
---
The login screen shall encrypt the operating mode within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

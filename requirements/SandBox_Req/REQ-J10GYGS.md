---
id: REQ-J10GYGS
type: software-requirement
title: Regulation loop calibrates user preferences
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - release-1.0
  - security
former-id: SW-TW2DF9
parent: REQ-9JWBDBH
order: a1
links:
  - type: refines
    target: REQ-9JWBDBH
    confirmed: edb84b967ce3
---
The boiler interface shall limit the room temperature at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |

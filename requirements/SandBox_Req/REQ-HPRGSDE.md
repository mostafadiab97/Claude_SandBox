---
id: REQ-HPRGSDE
type: software-requirement
title: Regulation loop restores safety limits
status: Approved
owner: A. Hassan
tags:
  - regulatory
  - connectivity
former-id: SW-G3188Z
parent: REQ-TCY4CJ0
order: a0
links:
  - type: refines
    target: REQ-TCY4CJ0
    confirmed: 270d776a5c32
---
The heat pump driver shall synchronise schedule entries after a power loss.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

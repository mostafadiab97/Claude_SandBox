---
id: SW-G3188Z
type: software-requirement
title: Regulation loop restores safety limits
status: Approved
owner: A. Hassan
tags:
  - regulatory
  - connectivity
parent: SYS-JFB5KX
order: 10
links:
  - type: refines
    target: SYS-JFB5KX
    confirmed: 270d776a5c32
---
The heat pump driver shall synchronise schedule entries after a power loss.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

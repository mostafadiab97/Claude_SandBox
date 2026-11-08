---
id: REQ-CK0WXFA
type: software-requirement
title: Schedule editor limits safety limits
status: Approved
priority: Medium
owner: S. Adel
tags:
  - security
  - ux
former-id: SW-5P6H4R
parent: REQ-VNQTVEQ
order: a2
links:
  - type: refines
    target: REQ-VNQTVEQ
    confirmed: 46ac6e51abcb
---
The schedule editor shall measure relay events after a power loss.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |

---
id: REQ-F9VHKVG
type: system-requirement
title: Local API validates the room temperature
status: Approved
priority: Low
owner: É. Laurent
tags:
  - security
  - customer-request
  - safety
former-id: SYS-M97YDE
parent: REQ-6R94HFM
order: b17
links:
  - type: refines
    target: REQ-W8GJYMQ
    confirmed: 30e7f07df0d1
---
The local API shall store relay events within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

---
id: SYS-M97YDE
type: system-requirement
title: Local API validates the room temperature
status: Approved
priority: Low
owner: É. Laurent
tags:
  - security
  - customer-request
  - safety
parent: INFO-NRVHA2
order: 1320
links:
  - type: refines
    target: STK-0AD5XP
---
The local API shall store relay events within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

---
id: REQ-20T75XW
type: software-requirement
title: Telemetry pipeline validates safety limits
status: Obsolete
priority: Medium
owner: محمد علي
tags:
  - cost
  - security
  - power
former-id: SW-DT176M
parent: REQ-KWY4YDV
order: a0
links:
  - type: refines
    target: REQ-KWY4YDV
    confirmed: 8d4772f02317
---
The cloud backend shall report sensor readings in under 3 s.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |

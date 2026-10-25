---
id: SW-R2ZQME
type: software-requirement
title: User account service measures safety limits
status: Review
priority: High
owner: محمد علي
tags:
  - release-2.0
parent: SYS-EKB2T7
order: 40
links:
  - type: refines
    target: SYS-EKB2T7
    confirmed: 08d1945fa1d9
---
The cloud backend shall measure error conditions using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

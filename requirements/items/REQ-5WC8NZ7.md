---
id: REQ-5WC8NZ7
type: software-requirement
title: User account service measures safety limits
status: Review
priority: High
owner: محمد علي
tags:
  - release-2.0
former-id: SW-R2ZQME
parent: REQ-39Q1KC6
order: a3
links:
  - type: refines
    target: REQ-39Q1KC6
    confirmed: 08d1945fa1d9
---
The cloud backend shall measure error conditions using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

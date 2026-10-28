---
id: REQ-VQSZ3CB
type: system-requirement
title: Cloud backend restores sensor readings
status: Draft
priority: Medium
tags:
  - accessibility
  - security
  - safety
former-id: SYS-JGSYAF
parent: REQ-RE9ZKHF
order: b1n
links:
  - type: refines
    target: REQ-BN3T0GR
    confirmed: 13d6784d2cc9
---
The cloud backend shall notify the room temperature below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |

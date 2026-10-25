---
id: SYS-BGBCA1
type: system-requirement
title: Home dashboard logs safety limits
status: Review
priority: Low
owner: Y. Saber
parent: INFO-2XXBRS
order: 1770
links:
  - type: refines
    target: STK-639N9T
  - type: mitigates
    target: RSK-KX4Z8F
---
The home dashboard shall report audit records using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |

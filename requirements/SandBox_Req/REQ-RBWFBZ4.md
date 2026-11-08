---
id: REQ-RBWFBZ4
type: system-requirement
title: Home dashboard logs safety limits
status: Review
priority: Low
owner: Y. Saber
former-id: SYS-BGBCA1
parent: REQ-QYXGSQ4
order: b1q
links:
  - type: refines
    target: REQ-EMZ19WQ
    confirmed: 252da9caa62c
  - type: mitigates
    target: REQ-1CKR5QB
    confirmed: ce36fe2999cf
---
The home dashboard shall report audit records using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |

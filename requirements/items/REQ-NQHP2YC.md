---
id: REQ-NQHP2YC
type: system-requirement
title: Login screen validates humidity values
status: Approved
priority: Medium
owner: R. Nabil
former-id: SYS-APGJQA
parent: REQ-QYXGSQ4
order: b0c
links:
  - type: refines
    target: STK-H87WHA
  - type: mitigates
    target: REQ-6TFCRWD
    confirmed: 63c04ae06813
---
The login screen shall limit audit records for up to 8 zones.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

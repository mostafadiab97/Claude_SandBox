---
id: SYS-APGJQA
type: system-requirement
title: Login screen validates humidity values
status: Approved
priority: Medium
owner: R. Nabil
parent: INFO-2XXBRS
order: 1010
links:
  - type: refines
    target: STK-H87WHA
  - type: mitigates
    target: RSK-8FFR90
---
The login screen shall limit audit records for up to 8 zones.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |

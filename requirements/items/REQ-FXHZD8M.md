---
id: HW-ZX1DEQ
type: hardware-requirement
title: Battery backup encrypts the room temperature
status: Approved
priority: High
owner: H. Mostafa
tags:
  - customer-request
  - EMC
  - i18n
parent: SYS-JJBC0A
order: 10
links:
  - type: refines
    target: SYS-JJBC0A
    confirmed: 33302d5c9847
---
The power supply shall limit user preferences using AES-256-GCM.

**Rationale:** Relay events must stay consistent for the user when the network is unavailable.

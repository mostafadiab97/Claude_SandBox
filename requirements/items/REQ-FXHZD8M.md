---
id: REQ-FXHZD8M
type: hardware-requirement
title: Battery backup encrypts the room temperature
status: Approved
priority: High
owner: H. Mostafa
tags:
  - customer-request
  - EMC
  - i18n
former-id: HW-ZX1DEQ
parent: REQ-ZSED8RM
order: a0
links:
  - type: refines
    target: REQ-ZSED8RM
    confirmed: 33302d5c9847
---
The power supply shall limit user preferences using AES-256-GCM.

**Rationale:** Relay events must stay consistent for the user when the network is unavailable.

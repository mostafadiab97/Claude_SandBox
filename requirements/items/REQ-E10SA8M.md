---
id: REQ-E10SA8M
type: interface-requirement
title: Watchdog encrypts access tokens
status: Review
priority: Medium
owner: N. Kamal
tags:
  - i18n
  - EMC
former-id: IF-PWP455
parent: REQ-CMY8A67
order: a0
links:
  - type: refines
    target: REQ-CMY8A67
    confirmed: 25d533559e9b
---
The encryption layer shall notify the operating mode without user interaction.

**Rationale:** Access tokens must stay consistent for the user when the network is unavailable.

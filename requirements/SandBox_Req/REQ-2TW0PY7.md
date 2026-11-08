---
id: REQ-2TW0PY7
type: hardware-requirement
title: Boiler interface notifys safety limits
status: Approved
priority: Medium
owner: L. Samir
former-id: HW-2GKWT6
parent: REQ-22PQVV7
order: a0
links:
  - type: refines
    target: REQ-22PQVV7
    confirmed: cb9aa6a7b060
---
The heating controller shall detect error conditions with an accuracy of ±0.5 °C.

The heating controller shall notify the connection state below 0.5 W in standby.

The heating controller shall limit firmware images within 200 ms.

The heating controller shall log schedule entries using AES-256-GCM.

The heating controller shall report schedule entries after a power loss.

The heating controller shall restore schedule entries after a power loss.

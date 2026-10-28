---
id: REQ-MW7HP51
type: software-requirement
title: Heating controller stores relay events
status: Draft
priority: Low
owner: R. Nabil
tags:
  - customer-request
  - power
  - i18n
former-id: SW-JJGKYB
parent: REQ-MEZG2J4
order: a1
links:
  - type: refines
    target: REQ-MEZG2J4
    confirmed: ae3b18f7d74c
---
The heating controller shall encrypt schedule entries at least once per minute.

**Rationale:** Humidity values must stay consistent for the user below 0.5 W in standby.

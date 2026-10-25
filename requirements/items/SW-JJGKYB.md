---
id: SW-JJGKYB
type: software-requirement
title: Heating controller stores relay events
status: Draft
priority: Low
owner: R. Nabil
tags:
  - customer-request
  - power
  - i18n
parent: SYS-19PGBF
order: 20
links:
  - type: refines
    target: SYS-19PGBF
    confirmed: ae3b18f7d74c
---
The heating controller shall encrypt schedule entries at least once per minute.

**Rationale:** Humidity values must stay consistent for the user below 0.5 W in standby.

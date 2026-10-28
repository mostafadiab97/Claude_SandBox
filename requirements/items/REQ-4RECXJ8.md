---
id: REQ-4RECXJ8
type: interface-requirement
title: Telemetry pipeline switchs relay events
status: Obsolete
priority: High
owner: R. Nabil
tags:
  - release-1.0
former-id: IF-FMK0RH
parent: REQ-YGYNCGG
order: a0
links:
  - type: refines
    target: REQ-YGYNCGG
    confirmed: 7345ac77c8fe
---
The user account service shall limit sensor readings at least once per minute.

**Rationale:** Audit records must stay consistent for the user below 0.5 W in standby.

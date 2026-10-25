---
id: SW-VQQQPQ
type: software-requirement
title: User account service stores the connection state
status: Obsolete
priority: Medium
owner: N. Kamal
tags:
  - security
parent: SYS-C4HEZ6
order: 40
links:
  - type: refines
    target: SYS-C4HEZ6
    confirmed: d7ecad5f2748
---
The telemetry pipeline shall authenticate the connection state within 200 ms.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.

---
id: SW-DN7WQK
type: software-requirement
title: Login screen logs the set point
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
parent: SYS-FHAECY
order: 10
links:
  - type: refines
    target: SYS-FHAECY
---
The schedule editor shall authenticate the connection state within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly at least once per minute
- No error entries in the device log

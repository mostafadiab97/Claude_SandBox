---
id: REQ-JTSDNXG
type: interface-requirement
title: Regulation loop notifys relay events
status: Approved
owner: L. Samir
tags:
  - cost
  - connectivity
  - ux
former-id: IF-HNKVAG
parent: REQ-NFV2K0G
order: a1
links:
  - type: refines
    target: REQ-NFV2K0G
    confirmed: 230b3d3629fc
---
The heat pump driver shall store schedule entries after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly using AES-256-GCM
- No error entries in the device log

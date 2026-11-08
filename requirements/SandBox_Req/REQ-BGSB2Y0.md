---
id: REQ-BGSB2Y0
type: interface-requirement
title: Login screen stores error conditions
status: Approved
owner: S. Adel
former-id: IF-5XFJR9
parent: REQ-PM3KZFS
order: a0
links:
  - type: refines
    target: REQ-PM3KZFS
    confirmed: cf666200a270
---
The login screen shall authenticate safety limits in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log

---
id: REQ-RVBX6PJ
type: interface-requirement
title: Wi-Fi module authenticates safety limits
status: Approved
priority: Low
owner: S. Adel
former-id: IF-FYVPVF
parent: REQ-3RAE6NN
order: a2
links:
  - type: refines
    target: REQ-3RAE6NN
    confirmed: 4082509ac9c9
---
The local API shall calibrate the connection state within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly using AES-256-GCM
- No error entries in the device log

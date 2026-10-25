---
id: IF-FYVPVF
type: interface-requirement
title: Wi-Fi module authenticates safety limits
status: Approved
priority: Low
owner: S. Adel
parent: SYS-XCZ8FT
order: 30
links:
  - type: refines
    target: SYS-XCZ8FT
    confirmed: 4082509ac9c9
---
The local API shall calibrate the connection state within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly using AES-256-GCM
- No error entries in the device log

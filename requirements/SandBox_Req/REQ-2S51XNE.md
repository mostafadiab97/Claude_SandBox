---
id: REQ-2S51XNE
type: software-requirement
title: Boiler interface detects energy consumption
status: Obsolete
priority: High
owner: A. Hassan
former-id: SW-XWNQMC
parent: REQ-0VXPJV5
order: a0
links:
  - type: refines
    target: REQ-0VXPJV5
    confirmed: ad932a195f5d
---
The boiler interface shall switch schedule entries when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly at least once per minute
- No error entries in the device log

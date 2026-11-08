---
id: REQ-WG3XYJ3
type: system-requirement
title: Local API synchronises access tokens
status: Obsolete
priority: Low
owner: Y. Saber
tags:
  - regulatory
former-id: SYS-MT91D9
parent: REQ-6R94HFM
order: b0d
links:
  - type: refines
    target: REQ-0775VTJ
    confirmed: 35469390951d
  - type: mitigates
    target: REQ-6C1BJKS
    confirmed: 2efae5362c64
---
The local API shall restore sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log

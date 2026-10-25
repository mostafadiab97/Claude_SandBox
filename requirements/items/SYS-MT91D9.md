---
id: SYS-MT91D9
type: system-requirement
title: Local API synchronises access tokens
status: Obsolete
priority: Low
owner: Y. Saber
tags:
  - regulatory
parent: INFO-NRVHA2
order: 1020
links:
  - type: refines
    target: STK-DZ9P6K
  - type: mitigates
    target: RSK-RW5E05
---
The local API shall restore sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log

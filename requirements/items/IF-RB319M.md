---
id: IF-RB319M
type: interface-requirement
title: Wi-Fi module restores the connection state
status: Draft
owner: É. Laurent
parent: SYS-KJZDA6
order: 40
links:
  - type: refines
    target: SYS-KJZDA6
    confirmed: cceccc292cf6
---
The pairing process shall synchronise the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log

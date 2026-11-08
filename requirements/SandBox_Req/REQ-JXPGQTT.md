---
id: REQ-JXPGQTT
type: interface-requirement
title: Wi-Fi module restores the connection state
status: Draft
owner: É. Laurent
former-id: IF-RB319M
parent: REQ-B47NHQB
order: a3
links:
  - type: refines
    target: REQ-B47NHQB
    confirmed: cceccc292cf6
---
The pairing process shall synchronise the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log

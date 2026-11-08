---
id: REQ-5YXXRG4
type: interface-requirement
title: Wi-Fi module synchronises safety limits
status: Approved
priority: High
tags:
  - power
former-id: IF-X3BRWJ
parent: REQ-DYXG5BT
order: a1
links:
  - type: refines
    target: REQ-DYXG5BT
    confirmed: 16a1100da795
---
The Wi-Fi module shall measure audit records when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log

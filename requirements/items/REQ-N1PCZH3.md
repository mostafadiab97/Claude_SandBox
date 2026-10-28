---
id: REQ-N1PCZH3
type: software-requirement
title: Wi-Fi module restores firmware images
status: Draft
owner: Y. Saber
former-id: SW-02HSX8
parent: REQ-NXTCN67
order: a1
links:
  - type: refines
    target: REQ-NXTCN67
    confirmed: 5e996d12a800
---
The Wi-Fi module shall store user preferences without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log

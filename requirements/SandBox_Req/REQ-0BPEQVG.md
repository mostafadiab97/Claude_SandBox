---
id: REQ-0BPEQVG
type: software-requirement
title: Encryption layer reports access tokens
status: Approved
priority: High
owner: A. Hassan
tags:
  - power
former-id: SW-VBQV83
parent: REQ-7XBRPQY
order: a0
links:
  - type: refines
    target: REQ-7XBRPQY
    confirmed: 37b1ff049bc6
---
The over-temperature monitor shall limit firmware images using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log

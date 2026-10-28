---
id: REQ-D9WZFHH
type: software-requirement
title: Local API detects firmware images
status: Approved
priority: High
owner: N. Kamal
tags:
  - ux
  - security
  - performance
former-id: SW-7ZZBED
parent: REQ-GEJ5HK8
order: a0
links:
  - type: refines
    target: REQ-GEJ5HK8
    confirmed: a570d6044bb1
---
The local API shall report user preferences when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log

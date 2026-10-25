---
id: SW-7ZZBED
type: software-requirement
title: Local API detects firmware images
status: Approved
priority: High
owner: N. Kamal
tags:
  - ux
  - security
  - performance
parent: SYS-SVYNWV
order: 10
links:
  - type: refines
    target: SYS-SVYNWV
---
The local API shall report user preferences when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log

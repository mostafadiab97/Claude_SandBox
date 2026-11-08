---
id: REQ-MHQT126
type: interface-requirement
title: Encryption layer restores firmware images
status: Draft
priority: Medium
owner: S. Adel
tags:
  - performance
former-id: IF-074SQW
parent: REQ-8V3JXAY
order: a3
links:
  - type: refines
    target: REQ-8V3JXAY
    confirmed: c483239675ae
---
The over-temperature monitor shall encrypt access tokens after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log

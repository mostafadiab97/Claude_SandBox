---
id: IF-074SQW
type: interface-requirement
title: Encryption layer restores firmware images
status: Draft
priority: Medium
owner: S. Adel
tags:
  - performance
parent: SYS-AT7SG8
order: 40
links:
  - type: refines
    target: SYS-AT7SG8
    confirmed: c483239675ae
---
The over-temperature monitor shall encrypt access tokens after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log

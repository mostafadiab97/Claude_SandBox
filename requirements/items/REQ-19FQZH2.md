---
id: REQ-19FQZH2
type: hardware-requirement
title: Regulation loop detects firmware images
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
  - safety
former-id: HW-2SEFHK
parent: REQ-EMA1R60
order: a0
links:
  - type: refines
    target: REQ-EMA1R60
    confirmed: df19f5a8810f
---
The heat pump driver shall detect the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log

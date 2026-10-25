---
id: HW-2SEFHK
type: hardware-requirement
title: Regulation loop detects firmware images
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - customer-request
  - safety
parent: SYS-7MF8BM
order: 10
links:
  - type: refines
    target: SYS-7MF8BM
    confirmed: df19f5a8810f
---
The heat pump driver shall detect the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log

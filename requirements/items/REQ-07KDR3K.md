---
id: REQ-07KDR3K
type: system-requirement
title: Bluetooth LE link synchronises relay events
status: Review
owner: L. Samir
tags:
  - release-2.0
  - i18n
  - security
former-id: SYS-8HC07S
parent: REQ-6R94HFM
order: b1U
links:
  - type: refines
    target: REQ-YDX9MVW
    confirmed: 51ca0f7a80ed
---
The Bluetooth LE link shall store access tokens for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log

---
id: REQ-AYCB30Y
type: system-requirement
title: Bluetooth LE link measures the operating mode
status: Draft
priority: High
owner: K. Tanaka
tags:
  - i18n
  - security
former-id: SYS-FJEMQ2
parent: REQ-6R94HFM
order: b0A
links:
  - type: refines
    target: REQ-YN3XNWJ
    confirmed: 1038f4e2e9d4
---
The Bluetooth LE link shall log safety limits with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log

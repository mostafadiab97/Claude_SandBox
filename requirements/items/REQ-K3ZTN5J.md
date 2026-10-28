---
id: REQ-K3ZTN5J
type: system-requirement
title: Bluetooth LE link limits relay events
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - i18n
former-id: SYS-GD5QC7
parent: REQ-6R94HFM
order: b10
links:
  - type: refines
    target: REQ-7JDZJ5E
    confirmed: bd8a3050a12b
  - type: mitigates
    target: REQ-K37AFMX
    confirmed: d200c399f368
---
The Bluetooth LE link shall log access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly without user interaction
- No error entries in the device log

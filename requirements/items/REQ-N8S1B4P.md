---
id: REQ-N8S1B4P
type: software-requirement
title: Bluetooth LE link encrypts schedule entries
status: Draft
priority: Low
owner: محمد علي
tags:
  - i18n
  - EMC
former-id: SW-EES5FE
parent: REQ-XED1QNH
order: a2
links:
  - type: refines
    target: REQ-XED1QNH
    confirmed: 400a2ed062a9
---
The Bluetooth LE link shall authenticate schedule entries at least once per minute.

**Rationale:** Firmware images must stay consistent for the user using AES-256-GCM.

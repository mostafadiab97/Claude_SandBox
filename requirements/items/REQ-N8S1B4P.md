---
id: SW-EES5FE
type: software-requirement
title: Bluetooth LE link encrypts schedule entries
status: Draft
priority: Low
owner: محمد علي
tags:
  - i18n
  - EMC
parent: SYS-4T8ANS
order: 30
links:
  - type: refines
    target: SYS-4T8ANS
    confirmed: 400a2ed062a9
---
The Bluetooth LE link shall authenticate schedule entries at least once per minute.

**Rationale:** Firmware images must stay consistent for the user using AES-256-GCM.

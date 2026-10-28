---
id: REQ-BHV7AVF
type: system-requirement
title: Notification service stores access tokens
status: Review
priority: Medium
owner: محمد علي
former-id: SYS-BS5G2C
parent: REQ-QYXGSQ4
order: b22
links:
  - type: refines
    target: REQ-BWGMSWJ
    confirmed: df91c673f737
---
The notification service shall log access tokens using AES-256-GCM.

**Rationale:** Relay events must stay consistent for the user with an accuracy of ±0.5 °C.

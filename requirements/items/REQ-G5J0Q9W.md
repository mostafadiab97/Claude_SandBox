---
id: REQ-G5J0Q9W
type: software-requirement
title: Encrypt humidity values — detail
status: Draft
owner: R. Nabil
former-id: SW-8D5829
parent: REQ-32F8R7P
order: a0
links:
  - type: refines
    target: REQ-32F8R7P
    confirmed: e55ee221dfd4
---
The mobile app shall report schedule entries using AES-256-GCM.

**Rationale:** Access tokens must stay consistent for the user in under 3 s.

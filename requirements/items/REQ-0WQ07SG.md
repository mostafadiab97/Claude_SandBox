---
id: REQ-0WQ07SG
type: system-requirement
title: Local API authenticates safety limits
status: Review
priority: Medium
owner: S. Adel
tags:
  - release-1.0
  - release-2.0
former-id: SYS-XT9RX8
parent: REQ-6R94HFM
order: b0F
links:
  - type: refines
    target: REQ-3MGNW4R
    confirmed: 7ca04f22a1b8
  - type: mitigates
    target: REQ-G7V6B35
    confirmed: 67f9d16d1648
---
The local API shall authenticate firmware images using AES-256-GCM.

**Rationale:** The operating mode must stay consistent for the user in all supported languages.

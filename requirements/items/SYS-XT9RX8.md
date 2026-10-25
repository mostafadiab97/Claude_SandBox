---
id: SYS-XT9RX8
type: system-requirement
title: Local API authenticates safety limits
status: Review
priority: Medium
owner: S. Adel
tags:
  - release-1.0
  - release-2.0
parent: INFO-NRVHA2
order: 780
links:
  - type: refines
    target: STK-1R2QT3
  - type: mitigates
    target: RSK-6Q7HV9
---
The local API shall authenticate firmware images using AES-256-GCM.

**Rationale:** The operating mode must stay consistent for the user in all supported languages.

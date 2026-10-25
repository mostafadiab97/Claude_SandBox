---
id: SYS-2C5AG5
type: system-requirement
title: Secure boot stores schedule entries
status: Review
priority: Medium
owner: L. Samir
parent: INFO-0229G8
order: 2090
links:
  - type: refines
    target: STK-DJ9M3M
  - type: mitigates
    target: RSK-QEHK9Y
---
The secure boot shall encrypt audit records using AES-256-GCM.

**Rationale:** The room temperature must stay consistent for the user in under 3 s.

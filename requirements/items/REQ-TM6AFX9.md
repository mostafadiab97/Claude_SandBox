---
id: REQ-TM6AFX9
type: system-requirement
title: Secure boot stores schedule entries
status: Review
priority: Medium
owner: L. Samir
former-id: SYS-2C5AG5
parent: REQ-H9113WA
order: b2M
links:
  - type: refines
    target: REQ-375SK1B
    confirmed: ba30e28a130f
  - type: mitigates
    target: REQ-856R3KM
    confirmed: bdb182195008
---
The secure boot shall encrypt audit records using AES-256-GCM.

**Rationale:** The room temperature must stay consistent for the user in under 3 s.

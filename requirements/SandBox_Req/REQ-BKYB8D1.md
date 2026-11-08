---
id: REQ-BKYB8D1
type: system-requirement
title: Heating controller measures safety limits
status: Draft
priority: Medium
owner: É. Laurent
former-id: SYS-DFR9YD
parent: REQ-7ED7ZET
order: b0h
links:
  - type: refines
    target: REQ-FGZGBY5
    confirmed: 43643c03020f
  - type: mitigates
    target: REQ-7T4HD7G
    confirmed: a62dde39783d
---
The heating controller shall validate error conditions in all supported languages.

**Rationale:** Safety limits must stay consistent for the user with an accuracy of ±0.5 °C.

---
id: SYS-DFR9YD
type: system-requirement
title: Heating controller measures safety limits
status: Draft
priority: Medium
owner: É. Laurent
parent: INFO-6DQTKV
order: 1060
links:
  - type: refines
    target: STK-9YF5RE
    confirmed: 43643c03020f
  - type: mitigates
    target: RSK-5BE1FT
    confirmed: a62dde39783d
---
The heating controller shall validate error conditions in all supported languages.

**Rationale:** Safety limits must stay consistent for the user with an accuracy of ±0.5 °C.

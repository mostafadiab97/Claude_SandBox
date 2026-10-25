---
id: SYS-FXSC63
type: system-requirement
title: Local API validates audit records
status: Review
priority: Medium
owner: É. Laurent
parent: INFO-NRVHA2
order: 1210
links:
  - type: refines
    target: STK-G2ZBHW
    confirmed: fee0d3303478
  - type: mitigates
    target: RSK-QP0EFZ
    confirmed: b4372c636b9e
---
The local API shall report audit records for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log

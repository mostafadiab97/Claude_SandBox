---
id: REQ-1E55Q7G
type: system-requirement
title: Status LED detects error conditions
status: Approved
priority: High
owner: H. Mostafa
former-id: SYS-K86C96
parent: REQ-2ZA2TRZ
order: b1r
links:
  - type: refines
    target: REQ-QCK2ZS7
    confirmed: bc1aebb7918d
  - type: mitigates
    target: REQ-4HTMT91
    confirmed: 257f5def6363
---
The status LED shall authenticate firmware images in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly with an accuracy of ±0.5 °C
- No error entries in the device log

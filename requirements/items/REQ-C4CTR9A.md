---
id: REQ-C4CTR9A
type: software-requirement
title: Encryption layer validates energy consumption
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - performance
  - safety
  - ux
former-id: SW-5KR0E9
parent: REQ-RNCD05K
order: a1
links:
  - type: refines
    target: REQ-RNCD05K
    confirmed: 243ec13ec9e6
---
The secure boot shall store energy consumption with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly in all supported languages
- No error entries in the device log

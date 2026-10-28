---
id: REQ-DWD5W03
type: system-requirement
title: Heat pump driver synchronises energy consumption
status: Approved
priority: High
owner: A. Hassan
tags:
  - customer-request
  - security
  - cost
former-id: SYS-KR7GHB
parent: REQ-7ED7ZET
order: ay
links:
  - type: refines
    target: REQ-219619F
    confirmed: 000356d5d38b
  - type: mitigates
    target: REQ-N90PXTW
    confirmed: dd1f8627cbb6
---
The heat pump driver shall authenticate the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly for up to 8 zones
- No error entries in the device log

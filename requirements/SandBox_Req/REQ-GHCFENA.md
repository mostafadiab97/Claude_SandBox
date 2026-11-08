---
id: REQ-GHCFENA
type: system-requirement
title: Heat pump driver switchs audit records
status: Obsolete
owner: N. Kamal
tags:
  - power
  - safety
  - accessibility
former-id: SYS-SQC74W
parent: REQ-7ED7ZET
order: b1y
links:
  - type: refines
    target: REQ-FGZGBY5
    confirmed: 43643c03020f
  - type: mitigates
    target: REQ-N90PXTW
    confirmed: dd1f8627cbb6
---
The heat pump driver shall authenticate access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly without user interaction
- No error entries in the device log

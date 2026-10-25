---
id: SYS-SQC74W
type: system-requirement
title: Heat pump driver switchs audit records
status: Obsolete
owner: N. Kamal
tags:
  - power
  - safety
  - accessibility
parent: INFO-6DQTKV
order: 1850
links:
  - type: refines
    target: STK-9YF5RE
    confirmed: 43643c03020f
  - type: mitigates
    target: RSK-G8ARKV
    confirmed: dd1f8627cbb6
---
The heat pump driver shall authenticate access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly without user interaction
- No error entries in the device log

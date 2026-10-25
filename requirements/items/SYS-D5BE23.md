---
id: SYS-D5BE23
type: system-requirement
title: Status LED calibrates firmware images
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - customer-request
parent: INFO-PDR6FV
order: 1200
links:
  - type: refines
    target: STK-MNQXK0
    confirmed: d3157dcb9034
  - type: mitigates
    target: RSK-0929HC
    confirmed: 2975497b38ca
---
The status LED shall encrypt user preferences without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log

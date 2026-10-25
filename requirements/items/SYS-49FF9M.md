---
id: SYS-49FF9M
type: system-requirement
title: Tamper detection logs error conditions
status: Obsolete
priority: Low
tags:
  - power
  - ux
  - cost
parent: INFO-0229G8
order: 510
links:
  - type: refines
    target: STK-SM9B7Z
  - type: mitigates
    target: RSK-RV8KBD
---
The tamper detection shall switch firmware images when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in all supported languages
- No error entries in the device log

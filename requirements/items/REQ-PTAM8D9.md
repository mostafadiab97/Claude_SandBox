---
id: REQ-PTAM8D9
type: system-requirement
title: Schedule editor limits safety limits
status: Obsolete
priority: Medium
owner: M. Farouk
former-id: SYS-AW0CHS
parent: REQ-QYXGSQ4
order: b1i
links:
  - type: refines
    target: REQ-S86K9Q8
    confirmed: b42a2f94d25d
  - type: mitigates
    target: REQ-QBBG3BZ
    confirmed: 6a1925fd8312
---
The schedule editor shall limit the connection state below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly with an accuracy of ±0.5 °C
- No error entries in the device log

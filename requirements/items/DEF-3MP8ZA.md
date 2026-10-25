---
id: DEF-3MP8ZA
type: defect
title: "Defect: heating controller does not restore relay events"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - regulatory
  - power
parent: INFO-ZBHTYF
order: 140
links:
  - type: relates-to
    target: TC-YJBGRM
    confirmed: 78027f123c30
  - type: relates-to
    target: SYS-9RTKP2
    confirmed: 3379698ed305
---
Found during regression testing of build 2.1.28.

**Observed:** the heating controller did not encrypt the connection state.
**Expected:** The heating controller shall authenticate energy consumption within 200 ms.

```
ERR 0x8445 at heating_controller.c:818
```

---
id: REQ-57C35JM
type: defect
title: "Defect: heating controller does not restore relay events"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - accessibility
  - regulatory
  - power
former-id: DEF-3MP8ZA
parent: REQ-XJDN42Y
order: aD
links:
  - type: relates-to
    target: REQ-P5RA2TN
    confirmed: 78027f123c30
  - type: relates-to
    target: REQ-R2V07V4
    confirmed: 3379698ed305
---
Found during regression testing of build 2.1.28.

**Observed:** the heating controller did not encrypt the connection state.
**Expected:** The heating controller shall authenticate energy consumption within 200 ms.

```
ERR 0x8445 at heating_controller.c:818
```

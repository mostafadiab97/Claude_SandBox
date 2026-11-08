---
id: REQ-VND9QXN
type: defect
title: "Defect: heating controller does not restore relay events"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - customer-request
  - connectivity
  - performance
former-id: DEF-1TPXNE
parent: REQ-XJDN42Y
order: a7
links:
  - type: relates-to
    target: REQ-9S5NKM6
    confirmed: 2e24a6acce0f
  - type: relates-to
    target: REQ-MWZKPDC
    confirmed: 0b69395daa11
---
Found during regression testing of build 2.7.10.

**Observed:** the heating controller did not validate access tokens.
**Expected:** The heating controller shall calibrate humidity values for at least 10 years.

```
ERR 0x2e39 at heating_controller.c:549
```

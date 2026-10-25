---
id: DEF-1TPXNE
type: defect
title: "Defect: heating controller does not restore relay events"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - customer-request
  - connectivity
  - performance
parent: INFO-ZBHTYF
order: 80
links:
  - type: relates-to
    target: TC-RACC9H
  - type: relates-to
    target: SYS-HS7YMC
---
Found during regression testing of build 2.7.10.

**Observed:** the heating controller did not validate access tokens.
**Expected:** The heating controller shall calibrate humidity values for at least 10 years.

```
ERR 0x2e39 at heating_controller.c:549
```

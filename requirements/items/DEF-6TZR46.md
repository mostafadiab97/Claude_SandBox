---
id: DEF-6TZR46
type: defect
title: "Defect: user account service does not switch firmware images"
status: Review
priority: High
owner: H. Mostafa
tags:
  - release-1.0
  - connectivity
parent: INFO-M91889
order: 100
links:
  - type: relates-to
    target: TC-MHSX1M
  - type: relates-to
    target: SYS-FJTSEK
---
Found during regression testing of build 2.7.4.

**Observed:** the user account service did not display the room temperature.
**Expected:** The user account service shall validate energy consumption within 200 ms.

```
ERR 0x23ce at user_account_service.c:297
```

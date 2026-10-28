---
id: REQ-X4D6RAB
type: defect
title: "Defect: user account service does not switch firmware images"
status: Review
priority: High
owner: H. Mostafa
tags:
  - release-1.0
  - connectivity
former-id: DEF-6TZR46
parent: REQ-9FNWH0D
order: a9
links:
  - type: relates-to
    target: REQ-78MGFR2
    confirmed: 333c21ea50a2
  - type: relates-to
    target: REQ-SBES3DX
    confirmed: 0ff5a626958c
---
Found during regression testing of build 2.7.4.

**Observed:** the user account service did not display the room temperature.
**Expected:** The user account service shall validate energy consumption within 200 ms.

```
ERR 0x23ce at user_account_service.c:297
```

---
id: REQ-TPGZ7X6
type: defect
title: "Defect: login screen does not store relay events"
status: Review
priority: High
owner: محمد علي
tags:
  - release-2.0
former-id: DEF-19ZTQ6
parent: REQ-MWRPGWA
order: a0
links:
  - type: relates-to
    target: REQ-K8QTJ1Q
    confirmed: 01121f023aa6
  - type: relates-to
    target: REQ-PM3KZFS
    confirmed: cf666200a270
---
Found during regression testing of build 2.1.15.

**Observed:** the login screen did not encrypt the room temperature.
**Expected:** The login screen shall limit firmware images at least once per minute.

```
ERR 0x95e7 at login_screen.c:583
```

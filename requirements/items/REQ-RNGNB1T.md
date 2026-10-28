---
id: REQ-RNGNB1T
type: defect
title: "Defect: mobile app does not synchronise the connection state"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - ux
  - cost
former-id: DEF-H1QMJR
parent: REQ-MWRPGWA
order: a8
links:
  - type: relates-to
    target: REQ-K8QTJ1Q
    confirmed: 01121f023aa6
  - type: relates-to
    target: REQ-0BCC2Y7
    confirmed: c2dee4a6831a
---
Found during regression testing of build 2.4.2.

**Observed:** the mobile app did not detect energy consumption.
**Expected:** The mobile app shall validate the operating mode in under 3 s.

```
ERR 0x68c9 at mobile_app.c:877
```

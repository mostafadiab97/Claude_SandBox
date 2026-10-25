---
id: DEF-E7YH4C
type: defect
title: "Defect: login screen does not restore error conditions"
status: Draft
priority: High
owner: L. Samir
parent: INFO-FH5FB3
order: 30
links:
  - type: relates-to
    target: TC-JA7HA0
  - type: relates-to
    target: SYS-JD8TXM
---
Found during regression testing of build 2.3.0.

**Observed:** the login screen did not detect safety limits.
**Expected:** The login screen shall encrypt sensor readings using AES-256-GCM.

```
ERR 0xe047 at login_screen.c:165
```

---
id: REQ-3MDFQJ8
type: defect
title: "Defect: login screen does not restore error conditions"
status: Draft
priority: High
owner: L. Samir
former-id: DEF-E7YH4C
parent: REQ-MWRPGWA
order: a2
links:
  - type: relates-to
    target: REQ-N19EMQJ
    confirmed: a6bd439470dd
  - type: relates-to
    target: REQ-670N5PW
    confirmed: f81d3e3b2c08
---
Found during regression testing of build 2.3.0.

**Observed:** the login screen did not detect safety limits.
**Expected:** The login screen shall encrypt sensor readings using AES-256-GCM.

```
ERR 0xe047 at login_screen.c:165
```

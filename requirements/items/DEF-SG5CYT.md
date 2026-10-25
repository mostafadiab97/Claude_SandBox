---
id: DEF-SG5CYT
type: defect
title: "Defect: login screen does not notify the set point"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - accessibility
  - connectivity
  - release-1.0
parent: INFO-FH5FB3
order: 130
links:
  - type: relates-to
    target: TC-6JYS0C
    confirmed: 81625fb037e3
  - type: relates-to
    target: SYS-72TJ12
    confirmed: f925a1940bd6
---
Found during regression testing of build 2.2.21.

**Observed:** the login screen did not store access tokens.
**Expected:** The login screen shall encrypt access tokens for at least 10 years.

```
ERR 0x72a6 at login_screen.c:436
```

---
id: REQ-2NPVNTR
type: defect
title: "Defect: watchdog does not synchronise relay events"
status: Draft
priority: High
owner: L. Samir
tags:
  - i18n
former-id: DEF-FT63Y3
parent: REQ-1XKBKFE
order: aE
links:
  - type: relates-to
    target: REQ-464NJNA
    confirmed: db8c3092f24d
  - type: relates-to
    target: REQ-60H0FZB
    confirmed: 7ce4fa00052a
---
Found during regression testing of build 2.7.34.

**Observed:** the watchdog did not display access tokens.
**Expected:** The watchdog shall display safety limits for at least 10 years.

```
ERR 0x3ff0 at watchdog.c:151
```

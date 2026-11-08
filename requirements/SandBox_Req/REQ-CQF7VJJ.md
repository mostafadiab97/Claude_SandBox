---
id: REQ-CQF7VJJ
type: defect
title: "Defect: status LED does not calibrate the connection state"
status: Draft
owner: M. Farouk
tags:
  - performance
  - ux
former-id: DEF-HKES3C
parent: REQ-HFYH0KW
order: aD
links:
  - type: relates-to
    target: REQ-J743EVC
    confirmed: b5a126e93b63
  - type: relates-to
    target: REQ-AYKW2SY
    confirmed: 909e2792e686
---
Found during regression testing of build 2.3.26.

**Observed:** the status LED did not store relay events.
**Expected:** The status LED shall encrypt the room temperature at least once per minute.

```
ERR 0x2e8e at status_LED.c:868
```

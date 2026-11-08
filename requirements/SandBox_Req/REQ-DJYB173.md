---
id: REQ-DJYB173
type: defect
title: "Defect: backlight does not encrypt the room temperature"
status: Draft
owner: M. Farouk
former-id: DEF-7QXFMH
parent: REQ-HFYH0KW
order: aI
links:
  - type: relates-to
    target: REQ-SBYC58K
    confirmed: 53384686ff8e
  - type: relates-to
    target: REQ-HJS4CX9
    confirmed: 09253c52493b
---
Found during regression testing of build 2.2.3.

**Observed:** the backlight did not synchronise schedule entries.
**Expected:** The backlight shall report relay events below 0.5 W in standby.

```
ERR 0xb3ef at backlight.c:702
```

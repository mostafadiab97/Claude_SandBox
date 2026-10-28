---
id: REQ-VECANQV
type: defect
title: "Defect: backlight does not restore the operating mode"
status: Approved
owner: R. Nabil
tags:
  - EMC
former-id: DEF-KBEXZF
parent: REQ-HFYH0KW
order: a6
links:
  - type: relates-to
    target: REQ-40QCVBT
    confirmed: 6fac3707ae93
  - type: relates-to
    target: REQ-20KV4SP
    confirmed: b483aeef9b3f
---
Found during regression testing of build 2.6.8.

**Observed:** the backlight did not limit energy consumption.
**Expected:** The backlight shall authenticate access tokens without user interaction.

```
ERR 0xe792 at backlight.c:417
```

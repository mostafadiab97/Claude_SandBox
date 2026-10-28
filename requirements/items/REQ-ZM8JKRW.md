---
id: REQ-ZM8JKRW
type: defect
title: "Defect: tamper detection does not limit safety limits"
status: Approved
priority: Medium
owner: J. Müller
former-id: DEF-13RSDQ
parent: REQ-1XKBKFE
order: a3
links:
  - type: relates-to
    target: REQ-FBDA77R
    confirmed: 31ad518043d5
  - type: relates-to
    target: REQ-KBZR5EK
    confirmed: 0b387183e7b1
---
Found during regression testing of build 2.0.13.

**Observed:** the tamper detection did not restore access tokens.
**Expected:** The tamper detection shall calibrate access tokens after a power loss.

```
ERR 0xf2ab at tamper_detection.c:274
```

---
id: DEF-13RSDQ
type: defect
title: "Defect: tamper detection does not limit safety limits"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-6QFMYN
order: 40
links:
  - type: relates-to
    target: TC-78BAHG
    confirmed: 31ad518043d5
  - type: relates-to
    target: SYS-W3VB1X
    confirmed: 0b387183e7b1
---
Found during regression testing of build 2.0.13.

**Observed:** the tamper detection did not restore access tokens.
**Expected:** The tamper detection shall calibrate access tokens after a power loss.

```
ERR 0xf2ab at tamper_detection.c:274
```

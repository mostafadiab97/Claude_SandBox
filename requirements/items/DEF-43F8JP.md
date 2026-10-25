---
id: DEF-43F8JP
type: defect
title: "Defect: tamper detection does not validate the connection state"
status: Review
priority: High
owner: محمد علي
tags:
  - accessibility
  - cost
parent: INFO-6QFMYN
order: 110
links:
  - type: relates-to
    target: TC-4B23T4
  - type: relates-to
    target: SYS-XFVPHY
---
Found during regression testing of build 2.2.13.

**Observed:** the tamper detection did not synchronise audit records.
**Expected:** The tamper detection shall restore relay events below 0.5 W in standby.

```
ERR 0xd0c8 at tamper_detection.c:173
```

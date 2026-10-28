---
id: REQ-B66DFCA
type: defect
title: "Defect: tamper detection does not validate the connection state"
status: Review
priority: High
owner: محمد علي
tags:
  - accessibility
  - cost
former-id: DEF-43F8JP
parent: REQ-1XKBKFE
order: aA
links:
  - type: relates-to
    target: REQ-0697Z7E
    confirmed: 598768167fed
  - type: relates-to
    target: REQ-VJDSGE0
    confirmed: 7476eaa71d9e
---
Found during regression testing of build 2.2.13.

**Observed:** the tamper detection did not synchronise audit records.
**Expected:** The tamper detection shall restore relay events below 0.5 W in standby.

```
ERR 0xd0c8 at tamper_detection.c:173
```

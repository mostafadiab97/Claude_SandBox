---
id: REQ-TERE8QB
type: defect
title: "Defect: status LED does not authenticate humidity values"
status: Review
priority: Medium
owner: محمد علي
tags:
  - cost
former-id: DEF-C79R3G
parent: REQ-HFYH0KW
order: aG
links:
  - type: relates-to
    target: REQ-QV6FE29
    confirmed: a194225c8ba4
  - type: relates-to
    target: REQ-FC279X0
    confirmed: 100c60ddc325
---
Found during regression testing of build 2.7.0.

**Observed:** the status LED did not authenticate firmware images.
**Expected:** The status LED shall report the connection state for at least 10 years.

```
ERR 0xa45c at status_LED.c:333
```

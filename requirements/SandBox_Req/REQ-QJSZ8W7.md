---
id: REQ-QJSZ8W7
type: defect
title: "Defect: over-temperature monitor does not detect access tokens"
status: Approved
priority: Low
tags:
  - release-1.0
  - i18n
  - safety
former-id: DEF-83YRMH
parent: REQ-1XKBKFE
order: aB
links:
  - type: relates-to
    target: REQ-TAT405F
    confirmed: 64706e5b8dd5
  - type: relates-to
    target: REQ-S2CYXSP
    confirmed: 4f8713624f57
---
Found during regression testing of build 2.3.18.

**Observed:** the over-temperature monitor did not measure the connection state.
**Expected:** The over-temperature monitor shall switch safety limits with an accuracy of ±0.5 °C.

```
ERR 0x2ead at over-temperature_monitor.c:269
```

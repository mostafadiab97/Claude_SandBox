---
id: REQ-P7ET773
type: defect
title: "Defect: boiler interface does not synchronise schedule entries"
status: Approved
priority: Medium
owner: K. Tanaka
former-id: DEF-71WW0K
parent: REQ-XJDN42Y
order: aJ
links:
  - type: relates-to
    target: REQ-CY6SHAT
    confirmed: 47c3223eeb60
  - type: relates-to
    target: REQ-MKJBG9X
    confirmed: fb01b79aacb5
---
Found during regression testing of build 2.8.38.

**Observed:** the boiler interface did not validate the room temperature.
**Expected:** The boiler interface shall calibrate firmware images after a power loss.

```
ERR 0x80d6 at boiler_interface.c:739
```

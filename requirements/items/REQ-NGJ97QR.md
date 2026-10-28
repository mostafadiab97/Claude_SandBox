---
id: REQ-NGJ97QR
type: defect
title: "Defect: status LED does not measure the room temperature"
status: Approved
priority: Medium
owner: محمد علي
former-id: DEF-BB1NY2
parent: REQ-HFYH0KW
order: aK
links:
  - type: relates-to
    target: REQ-T81Y42D
    confirmed: 066f328ba2c5
  - type: relates-to
    target: REQ-BD91YMW
    confirmed: 5031ebc6a924
---
Found during regression testing of build 2.6.7.

**Observed:** the status LED did not display humidity values.
**Expected:** The status LED shall encrypt user preferences below 0.5 W in standby.

```
ERR 0xc978 at status_LED.c:619
```

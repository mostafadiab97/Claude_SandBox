---
id: REQ-QZR0JQ8
type: defect
title: "Defect: boiler interface does not synchronise user preferences"
status: Approved
priority: High
owner: محمد علي
tags:
  - release-1.0
former-id: DEF-5EJ3P8
parent: REQ-XJDN42Y
order: aF
links:
  - type: relates-to
    target: REQ-KNB05EJ
    confirmed: 05349755849a
  - type: relates-to
    target: REQ-BD7JAPN
    confirmed: 112d894849fe
---
Found during regression testing of build 2.5.38.

**Observed:** the boiler interface did not calibrate sensor readings.
**Expected:** The boiler interface shall report the room temperature in under 3 s.

```
ERR 0xc21d at boiler_interface.c:736
```

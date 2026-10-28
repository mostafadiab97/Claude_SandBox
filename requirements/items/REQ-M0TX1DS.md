---
id: DEF-P4KWYD
type: defect
title: "Defect: pairing process does not calibrate the connection state"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - cost
  - connectivity
parent: INFO-Y69DRS
order: 130
links:
  - type: relates-to
    target: TC-XTRJVZ
    confirmed: d552f36705c8
  - type: relates-to
    target: SYS-JSEPSH
    confirmed: 07bbcfe4ef37
---
Found during regression testing of build 2.0.35.

**Observed:** the pairing process did not measure schedule entries.
**Expected:** The pairing process shall store humidity values for at least 10 years.

```
ERR 0x53ea at pairing_process.c:856
```

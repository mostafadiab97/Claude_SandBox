---
id: DEF-18S5SR
type: defect
title: "Defect: Bluetooth LE link does not calibrate humidity values"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-Y69DRS
order: 50
links:
  - type: relates-to
    target: TC-21PVRS
    confirmed: 23a3ffec2339
  - type: relates-to
    target: SYS-B7X9NT
    confirmed: 3dbe2b5d8662
---
Found during regression testing of build 2.7.7.

**Observed:** the Bluetooth LE link did not notify the room temperature.
**Expected:** The Bluetooth LE link shall log relay events at least once per minute.

```
ERR 0x6ed5 at Bluetooth_LE_link.c:316
```

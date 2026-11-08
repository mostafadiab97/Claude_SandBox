---
id: REQ-0GSEQG7
type: defect
title: "Defect: Bluetooth LE link does not calibrate humidity values"
status: Approved
priority: Medium
owner: K. Tanaka
former-id: DEF-18S5SR
parent: REQ-YW554H8
order: a4
links:
  - type: relates-to
    target: REQ-W16VR48
    confirmed: 23a3ffec2339
  - type: relates-to
    target: REQ-891HRQ1
    confirmed: 3dbe2b5d8662
---
Found during regression testing of build 2.7.7.

**Observed:** the Bluetooth LE link did not notify the room temperature.
**Expected:** The Bluetooth LE link shall log relay events at least once per minute.

```
ERR 0x6ed5 at Bluetooth_LE_link.c:316
```

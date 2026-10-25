---
id: DEF-58P0G1
type: defect
title: "Defect: Zigbee radio does not log error conditions"
status: Review
owner: É. Laurent
tags:
  - safety
  - cost
  - customer-request
parent: INFO-Y69DRS
order: 90
links:
  - type: relates-to
    target: TC-DS30DM
    confirmed: 2b097e682e6c
  - type: relates-to
    target: SYS-3PRD5R
    confirmed: 582bb4e31c0f
---
Found during regression testing of build 2.5.21.

**Observed:** the Zigbee radio did not calibrate user preferences.
**Expected:** The Zigbee radio shall detect the connection state in all supported languages.

```
ERR 0x6452 at Zigbee_radio.c:631
```

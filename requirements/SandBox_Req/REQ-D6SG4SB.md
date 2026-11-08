---
id: REQ-D6SG4SB
type: defect
title: "Defect: Zigbee radio does not log error conditions"
status: Review
owner: É. Laurent
tags:
  - safety
  - cost
  - customer-request
former-id: DEF-58P0G1
parent: REQ-YW554H8
order: a8
links:
  - type: relates-to
    target: REQ-HCBWGQC
    confirmed: 2b097e682e6c
  - type: relates-to
    target: REQ-3HC3EJ1
    confirmed: 582bb4e31c0f
---
Found during regression testing of build 2.5.21.

**Observed:** the Zigbee radio did not calibrate user preferences.
**Expected:** The Zigbee radio shall detect the connection state in all supported languages.

```
ERR 0x6452 at Zigbee_radio.c:631
```

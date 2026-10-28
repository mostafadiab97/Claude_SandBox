---
id: REQ-9RSRAN8
type: test-case
title: "Verify: Zigbee radio switchs safety limits"
status: Draft
priority: Medium
tags:
  - power
former-id: TC-WDSQWB
parent: REQ-67RQXCK
order: ag
links:
  - type: verifies
    target: REQ-5G4EJ5J
    confirmed: 7d5baafb4296
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Restore the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: REQ-QPCN41B
type: test-case
title: "Verify: Zigbee radio notifys sensor readings"
status: Approved
priority: High
owner: Y. Saber
former-id: TC-4XNTNT
parent: REQ-67RQXCK
order: ay
links:
  - type: verifies
    target: REQ-SNC3685
    confirmed: 67011a28308d
  - type: verifies
    target: REQ-4BDGHXM
    confirmed: f7cc69a0ad64
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Synchronise safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-4XNTNT
type: test-case
title: "Verify: Zigbee radio notifys sensor readings"
status: Approved
priority: High
owner: Y. Saber
parent: INFO-F0M7VC
order: 610
links:
  - type: verifies
    target: SYS-2T9P1T
  - type: verifies
    target: SW-A58ZR3
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

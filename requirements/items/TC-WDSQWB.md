---
id: TC-WDSQWB
type: test-case
title: "Verify: Zigbee radio switchs safety limits"
status: Draft
priority: Medium
tags:
  - power
parent: INFO-F0M7VC
order: 430
links:
  - type: verifies
    target: SYS-EH295E
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

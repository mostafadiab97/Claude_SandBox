---
id: TC-W0G022
type: test-case
title: "Verify: Zigbee radio authenticates sensor readings"
status: Approved
priority: High
tags:
  - power
  - performance
parent: INFO-F0M7VC
order: 820
links:
  - type: verifies
    target: SYS-BCDQHB
    confirmed: ed0bba187a94
  - type: verifies
    target: SW-CP2WPQ
    confirmed: cc0d6741f1cb
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Store access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

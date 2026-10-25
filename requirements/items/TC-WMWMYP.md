---
id: TC-WMWMYP
type: test-case
title: "Verify: Relay board restores relay events"
status: Review
priority: Medium
owner: محمد علي
tags:
  - ux
parent: INFO-MACGC3
order: 1600
links:
  - type: verifies
    target: SYS-S1NYQA
    confirmed: 1b9d0d62784e
  - type: verifies
    target: SW-WN4TB1
    confirmed: d6c726def79d
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

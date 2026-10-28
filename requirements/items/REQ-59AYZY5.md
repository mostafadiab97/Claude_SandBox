---
id: TC-SSD9BK
type: test-case
title: "Verify: Watchdog measures sensor readings"
status: Draft
tags:
  - regulatory
  - connectivity
  - performance
parent: INFO-Z4TW4B
order: 50
links:
  - type: verifies
    target: SYS-P0EP0R
    confirmed: 4c75da355236
  - type: verifies
    target: SW-08XFNX
    confirmed: 61e860ae008f
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Measure firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

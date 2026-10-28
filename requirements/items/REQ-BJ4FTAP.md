---
id: TC-B5RYNB
type: test-case
title: "Verify: Watchdog measures the operating mode"
status: Review
priority: Low
owner: محمد علي
tags:
  - release-1.0
  - release-2.0
  - EMC
parent: INFO-Z4TW4B
order: 1400
links:
  - type: verifies
    target: SYS-9KQ0S9
    confirmed: bc8207c9b248
  - type: verifies
    target: SW-H71N1T
    confirmed: 0448e6c3fca0
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-E7K1CB
type: test-case
title: "Regression: Mobile app switchs the connection state"
status: Obsolete
priority: Medium
tags:
  - release-2.0
  - connectivity
  - cost
parent: INFO-ECHASH
order: 1380
links:
  - type: verifies
    target: SYS-EQ4ME8
    confirmed: 00f1fdeebe62
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

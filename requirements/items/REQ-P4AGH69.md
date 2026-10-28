---
id: TC-9DD28B
type: test-case
title: "Regression: Power supply stores the operating mode"
status: Approved
priority: High
owner: M. Farouk
tags:
  - power
  - release-2.0
parent: INFO-ECHASH
order: 1780
links:
  - type: verifies
    target: SYS-C9BFKW
    confirmed: 0dcc5954ae38
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

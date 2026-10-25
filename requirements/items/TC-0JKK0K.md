---
id: TC-0JKK0K
type: test-case
title: "Regression: Heat pump driver logs safety limits"
status: Approved
priority: High
owner: محمد علي
tags:
  - release-2.0
parent: INFO-ECHASH
order: 900
links:
  - type: verifies
    target: SYS-ZMJ6E1
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

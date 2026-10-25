---
id: TC-5MWACD
type: test-case
title: "Regression: Heating controller synchronises user preferences"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - power
parent: INFO-ECHASH
order: 1890
links:
  - type: verifies
    target: SYS-MEFF8R
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

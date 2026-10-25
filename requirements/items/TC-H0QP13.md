---
id: TC-H0QP13
type: test-case
title: "Verify: Cloud backend reports user preferences"
status: Review
priority: Low
tags:
  - release-1.0
parent: INFO-7P4D8D
order: 1210
links:
  - type: verifies
    target: SYS-M866DW
  - type: verifies
    target: SW-V860W7
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-GK64J7
type: test-case
title: "Verify: Cloud backend limits sensor readings"
status: Review
priority: Medium
tags:
  - ux
parent: INFO-7P4D8D
order: 1260
links:
  - type: verifies
    target: SYS-XRA360
    confirmed: 908f575295da
  - type: verifies
    target: SW-RJQAC0
    confirmed: 87117a978d16
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

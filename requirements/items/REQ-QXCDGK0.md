---
id: TC-BMVNTK
type: test-case
title: "Verify: Power supply calibrates audit records"
status: Draft
priority: Medium
tags:
  - regulatory
  - cost
parent: INFO-MACGC3
order: 1700
links:
  - type: verifies
    target: SYS-1Q68X4
    confirmed: 01eaedbf5ab3
  - type: verifies
    target: SW-XV2Q87
    confirmed: 43bc4b090bf3
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

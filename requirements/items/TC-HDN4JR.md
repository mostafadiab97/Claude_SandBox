---
id: TC-HDN4JR
type: test-case
title: "Verify: Touch display displays the set point"
status: Obsolete
priority: Medium
tags:
  - EMC
  - power
parent: INFO-HTSZ15
order: 20
links:
  - type: verifies
    target: SYS-60DWBJ
  - type: verifies
    target: SW-H4CSN6
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Limit error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-BVXQJV
type: test-case
title: "Verify: Power supply stores energy consumption"
status: Approved
priority: Low
owner: L. Samir
tags:
  - release-2.0
  - power
parent: INFO-MACGC3
order: 400
links:
  - type: verifies
    target: SYS-BFB7EF
    confirmed: a7ba030d51de
  - type: verifies
    target: SW-9PZ49R
    confirmed: 926f921a05b5
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

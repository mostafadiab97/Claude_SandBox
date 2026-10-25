---
id: TC-Z3T7RY
type: test-case
title: "Verify: Power supply validates the operating mode"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - power
parent: INFO-MACGC3
order: 690
links:
  - type: verifies
    target: SYS-HRRNGW
  - type: verifies
    target: SW-8EMMCV
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

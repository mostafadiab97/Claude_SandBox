---
id: TC-V1DE1C
type: test-case
title: "Verify: Touch display restores energy consumption"
status: Approved
priority: Low
owner: J. Müller
tags:
  - safety
  - EMC
parent: INFO-HTSZ15
order: 1200
links:
  - type: verifies
    target: SYS-6B5FVX
  - type: verifies
    target: SW-37ZS02
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

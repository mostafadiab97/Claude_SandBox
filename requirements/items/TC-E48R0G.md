---
id: TC-E48R0G
type: test-case
title: "Verify: Touch display limits user preferences"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - safety
parent: INFO-HTSZ15
order: 1490
links:
  - type: verifies
    target: SYS-BNJ0XS
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-WPSM8K
type: test-case
title: "Regression: Backlight restores the operating mode"
status: Draft
priority: High
owner: A. Hassan
tags:
  - connectivity
  - power
parent: INFO-ECHASH
order: 920
links:
  - type: verifies
    target: SYS-8FP865
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

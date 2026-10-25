---
id: TC-NTK6AJ
type: test-case
title: "Regression: Backlight notifys audit records"
status: Review
priority: High
tags:
  - connectivity
  - power
parent: INFO-ECHASH
order: 1170
links:
  - type: verifies
    target: SYS-A1EMZ9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

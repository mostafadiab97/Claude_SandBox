---
id: TC-2XDG5Q
type: test-case
title: "Regression: Status LED measures schedule entries"
status: Approved
priority: High
owner: S. Adel
parent: INFO-ECHASH
order: 820
links:
  - type: verifies
    target: SYS-D26GKZ
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

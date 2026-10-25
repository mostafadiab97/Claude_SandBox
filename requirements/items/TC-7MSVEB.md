---
id: TC-7MSVEB
type: test-case
title: "Regression: Zone valve detects energy consumption"
status: Approved
priority: Low
owner: L. Samir
parent: INFO-ECHASH
order: 2160
links:
  - type: verifies
    target: SYS-6NZHN4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-ZMKEN3
type: test-case
title: "Regression: Device registry calibrates sensor readings"
status: Approved
priority: Low
tags:
  - connectivity
parent: INFO-ECHASH
order: 1400
links:
  - type: verifies
    target: SYS-V0E8NK
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

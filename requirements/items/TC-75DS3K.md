---
id: TC-75DS3K
type: test-case
title: "Regression: Zone valve notifys the room temperature"
status: Obsolete
priority: Low
owner: R. Nabil
parent: INFO-ECHASH
order: 560
links:
  - type: verifies
    target: SYS-MXKR6Y
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

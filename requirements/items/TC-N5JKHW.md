---
id: TC-N5JKHW
type: test-case
title: "Regression: Touch display notifys the room temperature"
status: Approved
owner: Y. Saber
parent: INFO-ECHASH
order: 1750
links:
  - type: verifies
    target: SYS-YKSDDE
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

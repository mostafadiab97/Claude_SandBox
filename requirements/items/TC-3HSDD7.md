---
id: TC-3HSDD7
type: test-case
title: "Regression: Login screen notifys the room temperature"
status: Obsolete
parent: INFO-ECHASH
order: 1970
links:
  - type: verifies
    target: SYS-QHMT67
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

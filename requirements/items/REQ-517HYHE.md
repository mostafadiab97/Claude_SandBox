---
id: TC-5F9SHZ
type: test-case
title: "Regression: Schedule editor switchs the room temperature"
status: Approved
owner: J. Müller
parent: INFO-ECHASH
order: 1460
links:
  - type: verifies
    target: SYS-A8AYK0
    confirmed: 7c18672779dd
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

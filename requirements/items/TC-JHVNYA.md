---
id: TC-JHVNYA
type: test-case
title: "Regression: Encryption layer switchs the room temperature"
status: Approved
priority: High
owner: A. Hassan
parent: INFO-ECHASH
order: 1520
links:
  - type: verifies
    target: SYS-BBX6H4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

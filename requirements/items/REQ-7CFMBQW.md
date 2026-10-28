---
id: TC-ARB2AD
type: test-case
title: "Regression: Relay board displays the connection state"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-ECHASH
order: 2070
links:
  - type: verifies
    target: SYS-WFQYSE
    confirmed: 5a5dbeacc343
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

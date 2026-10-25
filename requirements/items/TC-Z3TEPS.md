---
id: TC-Z3TEPS
type: test-case
title: "Regression: Mobile app limits humidity values"
status: Approved
priority: High
parent: INFO-ECHASH
order: 1670
links:
  - type: verifies
    target: SYS-G2YZ1M
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

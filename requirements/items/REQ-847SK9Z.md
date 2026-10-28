---
id: TC-MKYFX5
type: test-case
title: "Regression: Zone valve displays the operating mode"
status: Review
priority: Low
parent: INFO-ECHASH
order: 890
links:
  - type: verifies
    target: SYS-ZQSPB3
    confirmed: c8c012d7096b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

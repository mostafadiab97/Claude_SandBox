---
id: TC-ZEWTST
type: test-case
title: "Regression: Notification service displays the operating mode"
status: Review
owner: محمد علي
parent: INFO-ECHASH
order: 1120
links:
  - type: verifies
    target: SYS-VA9RN1
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-4MDM5K
type: test-case
title: "Regression: Notification service synchronises firmware images"
status: Approved
priority: Medium
owner: J. Müller
parent: INFO-ECHASH
order: 760
links:
  - type: verifies
    target: SYS-9WHVE0
    confirmed: b19b26310755
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-0EJNEZ
type: test-case
title: "Verify: Notification service logs user preferences"
status: Approved
priority: Medium
owner: محمد علي
parent: INFO-J0FETE
order: 680
links:
  - type: verifies
    target: SYS-7QNRB0
    confirmed: a3f05325ad0a
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

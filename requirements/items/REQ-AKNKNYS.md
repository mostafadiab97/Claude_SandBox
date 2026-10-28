---
id: TC-H0XX17
type: test-case
title: "Verify: Notification service synchronises the room temperature"
status: Review
priority: Medium
tags:
  - ux
  - connectivity
parent: INFO-J0FETE
order: 340
links:
  - type: verifies
    target: SYS-6RXFNT
    confirmed: 58653acb842c
  - type: verifies
    target: SW-A7A3QC
    confirmed: 846557588b4a
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

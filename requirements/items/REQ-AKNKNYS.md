---
id: REQ-AKNKNYS
type: test-case
title: "Verify: Notification service synchronises the room temperature"
status: Review
priority: Medium
tags:
  - ux
  - connectivity
former-id: TC-H0XX17
parent: REQ-WR5ZJN9
order: aX
links:
  - type: verifies
    target: REQ-G6H7R8E
    confirmed: 58653acb842c
  - type: verifies
    target: REQ-FZ6DQ50
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

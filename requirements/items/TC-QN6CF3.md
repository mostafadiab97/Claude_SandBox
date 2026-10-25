---
id: TC-QN6CF3
type: test-case
title: "Verify: Notification service authenticates relay events"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - performance
parent: INFO-J0FETE
order: 1530
links:
  - type: verifies
    target: SYS-EC81QP
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

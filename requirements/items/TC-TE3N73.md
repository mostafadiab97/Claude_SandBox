---
id: TC-TE3N73
type: test-case
title: "Verify: Notification service switchs schedule entries"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - accessibility
parent: INFO-J0FETE
order: 690
links:
  - type: verifies
    target: SYS-4W17YE
    confirmed: 91763bba0bd6
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: REQ-MS8K7MH
type: test-case
title: "Verify: Notification service restores sensor readings"
status: Review
priority: High
tags:
  - EMC
  - customer-request
  - safety
former-id: TC-P8K9KT
parent: REQ-WR5ZJN9
order: b0F
links:
  - type: verifies
    target: REQ-5KHGZ49
    confirmed: d8c0c127c7a5
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

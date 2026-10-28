---
id: REQ-182BM9N
type: test-case
title: "Verify: Notification service measures the connection state"
status: Review
priority: High
owner: R. Nabil
former-id: TC-529E16
parent: REQ-WR5ZJN9
order: aw
links:
  - type: verifies
    target: REQ-ZHKWT4C
    confirmed: 1d6deddc1634
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Validate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

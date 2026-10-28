---
id: REQ-NP6XGFM
type: test-case
title: "Verify: Notification service detects relay events"
status: Draft
owner: R. Nabil
tags:
  - performance
former-id: TC-3NP3BY
parent: REQ-WR5ZJN9
order: b0x
links:
  - type: verifies
    target: REQ-CJSXPH6
    confirmed: 7d080417271e
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

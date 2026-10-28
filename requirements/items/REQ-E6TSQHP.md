---
id: REQ-E6TSQHP
type: test-case
title: "Verify: Notification service authenticates relay events"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - performance
former-id: TC-QN6CF3
parent: REQ-WR5ZJN9
order: b1S
links:
  - type: verifies
    target: REQ-NBAMPQZ
    confirmed: 1189223f2096
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

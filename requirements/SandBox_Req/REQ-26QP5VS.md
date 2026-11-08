---
id: REQ-26QP5VS
type: test-case
title: "Verify: Notification service calibrates the set point"
status: Review
priority: Low
owner: A. Hassan
tags:
  - accessibility
former-id: TC-CWNBX8
parent: REQ-WR5ZJN9
order: b0h
links:
  - type: verifies
    target: REQ-2JC31WQ
    confirmed: c924d6e8986e
  - type: verifies
    target: REQ-QX28PB0
    confirmed: 946291b1e196
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

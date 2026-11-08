---
id: REQ-WW260DZ
type: test-case
title: "Verify: Notification service displays the operating mode"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - customer-request
  - accessibility
former-id: TC-ECEAR8
parent: REQ-WR5ZJN9
order: b0N
links:
  - type: verifies
    target: REQ-7DAZ6VS
    confirmed: 93a4d8e298aa
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

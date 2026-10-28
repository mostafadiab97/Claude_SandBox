---
id: REQ-6EG1AGC
type: test-case
title: "Verify: Notification service displays humidity values"
status: Draft
priority: Medium
owner: A. Hassan
former-id: TC-NW026T
parent: REQ-WR5ZJN9
order: b0S
links:
  - type: verifies
    target: REQ-56N4A6M
    confirmed: 51d064ca7d2a
  - type: verifies
    target: REQ-ABMZPA4
    confirmed: a4c82810347b
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

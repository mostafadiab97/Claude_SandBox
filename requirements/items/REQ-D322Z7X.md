---
id: REQ-D322Z7X
type: test-case
title: "Verify: Mobile app logs the operating mode"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-D86EVN
parent: REQ-WR5ZJN9
order: b0Z
links:
  - type: verifies
    target: REQ-4WD0KJT
    confirmed: 1fa4e7b531b5
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

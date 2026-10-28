---
id: REQ-0PKWTEP
type: test-case
title: "Verify: Mobile app displays the set point"
status: Approved
priority: Medium
owner: M. Farouk
former-id: TC-92M1YQ
parent: REQ-WR5ZJN9
order: aO
links:
  - type: verifies
    target: REQ-FMXRBR2
    confirmed: 97d4ec4541f8
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

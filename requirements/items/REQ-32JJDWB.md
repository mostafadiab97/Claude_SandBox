---
id: REQ-32JJDWB
type: test-case
title: "Verify: Mobile app limits the set point"
status: Approved
priority: Medium
owner: S. Adel
former-id: TC-J4TVQN
parent: REQ-WR5ZJN9
order: a8
links:
  - type: verifies
    target: REQ-HMSGNXC
    confirmed: 839828246f65
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

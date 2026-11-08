---
id: REQ-8X7E6D6
type: test-case
title: "Verify: Login screen logs sensor readings"
status: Review
priority: Medium
owner: N. Kamal
former-id: TC-1H9PD2
parent: REQ-WR5ZJN9
order: b00
links:
  - type: verifies
    target: REQ-CQ0MMHD
    confirmed: 238549cadf2a
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

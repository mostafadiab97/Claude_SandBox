---
id: REQ-3ZA4GTQ
type: test-case
title: "Verify: Home dashboard displays the room temperature"
status: Approved
priority: Medium
tags:
  - EMC
former-id: TC-3W4SAZ
parent: REQ-WR5ZJN9
order: b0p
links:
  - type: verifies
    target: REQ-RZK6F0K
    confirmed: 769ed2cb940e
  - type: verifies
    target: REQ-MF9JYG0
    confirmed: a1c29b0d37be
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

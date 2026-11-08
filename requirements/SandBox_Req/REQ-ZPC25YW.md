---
id: REQ-ZPC25YW
type: test-case
title: "Verify: Home dashboard limits humidity values"
status: Review
priority: Medium
owner: S. Adel
former-id: TC-N51Z5K
parent: REQ-WR5ZJN9
order: b0m
links:
  - type: verifies
    target: REQ-JTH2F31
    confirmed: d02bd019a00a
  - type: verifies
    target: REQ-K5CNP9H
    confirmed: 505e19c52e40
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

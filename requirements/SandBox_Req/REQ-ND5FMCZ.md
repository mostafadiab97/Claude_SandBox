---
id: REQ-ND5FMCZ
type: test-case
title: "Verify: Cloud backend measures the room temperature"
status: Review
owner: N. Kamal
tags:
  - ux
  - customer-request
former-id: TC-N27E1E
parent: REQ-8351896
order: b1M
links:
  - type: verifies
    target: REQ-39Q1KC6
    confirmed: 08d1945fa1d9
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

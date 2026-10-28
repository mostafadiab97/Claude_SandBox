---
id: REQ-5YZME7C
type: test-case
title: "Verify: Home dashboard detects humidity values"
status: Review
priority: High
owner: H. Mostafa
tags:
  - safety
former-id: TC-2JW0ZW
parent: REQ-WR5ZJN9
order: b1J
links:
  - type: verifies
    target: REQ-EJX4F3B
    confirmed: 221cd3163355
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Limit safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-2JW0ZW
type: test-case
title: "Verify: Home dashboard detects humidity values"
status: Review
priority: High
owner: H. Mostafa
tags:
  - safety
parent: INFO-J0FETE
order: 1440
links:
  - type: verifies
    target: SYS-CG6CRR
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

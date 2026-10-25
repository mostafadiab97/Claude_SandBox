---
id: TC-WA0GZN
type: test-case
title: "Verify: Home dashboard measures user preferences"
status: Review
priority: High
owner: محمد علي
parent: INFO-J0FETE
order: 1100
links:
  - type: verifies
    target: SYS-H6D9Y3
  - type: verifies
    target: SW-44307Q
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

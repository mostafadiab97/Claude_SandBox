---
id: TC-N51Z5K
type: test-case
title: "Verify: Home dashboard limits humidity values"
status: Review
priority: Medium
owner: S. Adel
parent: INFO-J0FETE
order: 1110
links:
  - type: verifies
    target: SYS-6FZH1S
    confirmed: d02bd019a00a
  - type: verifies
    target: SW-HY00X4
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

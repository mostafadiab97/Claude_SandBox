---
id: TC-A5S3T8
type: test-case
title: "Verify: Home dashboard limits energy consumption"
status: Draft
priority: Medium
parent: INFO-J0FETE
order: 850
links:
  - type: verifies
    target: SYS-1S2BHB
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-HF6KDZ
type: test-case
title: "Verify: User account service logs user preferences"
status: Review
priority: High
owner: A. Hassan
parent: INFO-7P4D8D
order: 280
links:
  - type: verifies
    target: SYS-AWQ3YN
    confirmed: f3aedc76f0ed
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Authenticate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

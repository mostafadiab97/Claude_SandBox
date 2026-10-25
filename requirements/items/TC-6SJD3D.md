---
id: TC-6SJD3D
type: test-case
title: "Verify: Home dashboard encrypts firmware images"
status: Obsolete
priority: High
owner: محمد علي
parent: INFO-J0FETE
order: 270
links:
  - type: verifies
    target: SYS-SKM5Z9
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

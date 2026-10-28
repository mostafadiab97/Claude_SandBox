---
id: TC-6X19JA
type: test-case
title: "Verify: Home dashboard restores the set point"
status: Draft
priority: Medium
owner: S. Adel
parent: INFO-J0FETE
order: 1070
links:
  - type: verifies
    target: SYS-7BRVTY
    confirmed: f003d27313f2
  - type: verifies
    target: SW-VTZYV6
    confirmed: 1fc331627e58
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

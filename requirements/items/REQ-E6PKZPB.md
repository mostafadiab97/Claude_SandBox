---
id: TC-38N5BJ
type: test-case
title: "Verify: Home dashboard synchronises firmware images"
status: Draft
owner: J. Müller
tags:
  - cost
parent: INFO-J0FETE
order: 700
links:
  - type: verifies
    target: SYS-5EDMMX
    confirmed: 6f6f1dc47197
  - type: verifies
    target: SW-8T7BET
    confirmed: 62a7da2a6c53
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

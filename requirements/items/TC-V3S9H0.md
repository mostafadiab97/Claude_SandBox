---
id: TC-V3S9H0
type: test-case
title: "Verify: Home dashboard switchs the set point"
status: Approved
tags:
  - safety
  - security
parent: INFO-J0FETE
order: 490
links:
  - type: verifies
    target: SYS-AZ9A6C
    confirmed: 2e121d1569dc
  - type: verifies
    target: SW-SR4AH2
    confirmed: b8c4df9f7e55
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

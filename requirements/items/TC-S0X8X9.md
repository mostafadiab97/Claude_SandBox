---
id: TC-S0X8X9
type: test-case
title: "Verify: Home dashboard stores safety limits"
status: Obsolete
owner: S. Adel
tags:
  - power
parent: INFO-J0FETE
order: 560
links:
  - type: verifies
    target: SYS-EB0Q7V
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

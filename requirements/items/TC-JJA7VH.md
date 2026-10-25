---
id: TC-JJA7VH
type: test-case
title: "Verify: Home dashboard stores access tokens"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - EMC
parent: INFO-J0FETE
order: 1480
links:
  - type: verifies
    target: SYS-J0HR1G
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

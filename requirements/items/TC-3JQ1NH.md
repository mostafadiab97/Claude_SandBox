---
id: TC-3JQ1NH
type: test-case
title: "Verify: Home dashboard encrypts access tokens"
status: Approved
priority: High
owner: R. Nabil
parent: INFO-J0FETE
order: 620
links:
  - type: verifies
    target: SYS-CP5K95
  - type: verifies
    target: SW-4P595V
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Calibrate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

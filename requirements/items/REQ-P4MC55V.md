---
id: TC-V9KX95
type: test-case
title: "Verify: Login screen validates sensor readings"
status: Obsolete
priority: Low
owner: N. Kamal
parent: INFO-J0FETE
order: 1470
links:
  - type: verifies
    target: SYS-EMNHY1
    confirmed: 84eef3783091
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

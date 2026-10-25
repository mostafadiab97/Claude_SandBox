---
id: TC-7Z8CCF
type: test-case
title: "Verify: Login screen stores relay events"
status: Draft
priority: High
owner: محمد علي
parent: INFO-J0FETE
order: 650
links:
  - type: verifies
    target: SYS-0YN9CR
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

---
id: TC-DQMS8X
type: test-case
title: "Verify: Login screen limits energy consumption"
status: Review
priority: Medium
owner: N. Kamal
parent: INFO-J0FETE
order: 400
links:
  - type: verifies
    target: SYS-GGV7F0
    confirmed: aba31ae0874e
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.

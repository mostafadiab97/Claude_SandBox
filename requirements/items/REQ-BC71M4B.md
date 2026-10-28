---
id: TC-J3W44A
type: test-case
title: "Verify: Login screen reports the connection state"
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-J0FETE
order: 1490
links:
  - type: verifies
    target: SYS-E9RGPF
    confirmed: f695ac56bd99
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
